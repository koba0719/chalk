<template>
  <div>
    <b-navbar toggleable="lg" type="dark" sticky="true">
      <b-navbar-brand href="#">Chalk</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"/>

      <!-- ログイン時条件分岐(メニューを表示するか)-->
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="#">Link</b-nav-item>
          <b-nav-item href="#" disabled>Disabled</b-nav-item>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-item-dropdown right>
            <!-- Using 'button-content' slot -->
            <!-- ログイン時条件分岐(ログインボタンか、ユーザー機能ドロップダウンか。)-->
            <template slot="button-content"><em>User</em></template>
            <b-dropdown-item href="#">Profile</b-dropdown-item>
            <b-dropdown-item href="#">Sign Out</b-dropdown-item>
          </b-nav-item-dropdown>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
    <div>
      <nuxt/>
    </div>
  </div>
</template>
<style>
  .navbar {
    background-color: #0079BF;
  }

  .navbar-brand {
    font-weight: bold;
    font-size: 2em;
  }
</style>
