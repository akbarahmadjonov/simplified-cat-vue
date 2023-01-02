<template>
  <div>
    <div>
      <b-navbar toggleable="lg" type="dark" variant="info">
        <b-navbar-brand href="#">iBox.com</b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item href="#">Link</b-nav-item>
            <b-nav-item href="#" disabled>User disabled</b-nav-item>
            <div class="text-center">
              <b-button variant="light">
                My Profile
                <b-badge variant="light"
                  >9 <span class="sr-only">unread messages</span></b-badge
                >
              </b-button>
            </div>
          </b-navbar-nav>

          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <b-nav-form>
              <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
              <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
            </b-nav-form>

            <b-nav-item-dropdown class="languageDrop" text="Lang" right>
              <b-dropdown-item href="#">EN</b-dropdown-item>
              <b-dropdown-item href="#">ES</b-dropdown-item>
              <b-dropdown-item href="#">RU</b-dropdown-item>
              <b-dropdown-item href="#">FA</b-dropdown-item>
            </b-nav-item-dropdown>

            <b-nav-item-dropdown right>
              <!-- Using 'button-content' slot -->
              <template #button-content>
                <img class="profile" src="~@/assets/myProfile.jpg" alt="" /><em
                  >My profile</em
                >
              </template>
              <b-dropdown-item href="#">
                <font class="Icons" :icon="['fas', 'user']" />Profile</b-dropdown-item
              >
              <b-dropdown-item href="#">
                <font class="Icons" :icon="['fas', 'cog']" />Settings</b-dropdown-item
              >

              <b-dropdown-item href="#">
                <font class="Icons" :icon="['fas', 'tags']" />Discount</b-dropdown-item
              >
              <b-dropdown-item href="#">
                <font class="Icons" :icon="['fas', 'moon']" />Dark Mode</b-dropdown-item
              >
              <b-dropdown-item href="#">
                <font class="Icons" :icon="['fas', 'sign-in-alt']" />Sign
                Out</b-dropdown-item
              >
            </b-nav-item-dropdown>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
  </div>
</template>
<style scoped>
.Icons {
  color: #17a2b8;
  margin-right: 10px;
  font-weight: bold;
}

.Icons {
  color: #17a2b8;
  margin-right: 10px;
  font-weight: bold;
}

.Icons {
  color: #17a2b8;
  margin-right: 10px;
  font-weight: bold;
}

.languageDrop {
  margin: 0 20px;
  display: flex;
  align-items: center;
}

.profile {
  width: 40px;
  border-radius: 50%;
  margin-right: 10px;
}
</style>
