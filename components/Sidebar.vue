<template>
  <div>
    <!-- Sidebar -->
    <div
      class="hidden lg:block fixed lg:max-w-[295px] w-full overflow-y-auto h-full bg-white z-[999]"
      id="sidebarHRIS"
    >
      <div class="px-6 py-[50px] gap-y-[50px] flex flex-col">
        <div class="flex items-center justify-between">
          <nuxt-link to="#" class="flex justify-center">
            <img src="/assets/svgs/logo-type.svg" alt="" />
          </nuxt-link>
          <nuxt-link to="#" id="toggleCloseSidebar" class="lg:hidden">
            <svg
              class="w-6 h-6 text-dark"
              fill="none"
              stroke="currentColor"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M6 18L18 6M6 6l12 12"
              ></path>
            </svg>
          </nuxt-link>
        </div>
        <div class="flex flex-col gap-4">
          <div class="text-sm text-grey">Daily Use</div>
          <nuxt-link :to="{ name: 'companies-id' }" class="nav-link active">
            <img src="/assets/svgs/ic-grid.svg" alt="" />
            Overview
          </nuxt-link>
          <nuxt-link :to="{ name: 'companies-id-employees' }" class="nav-link">
            <img src="/assets/svgs/ic-users.svg" alt="" />
            Employees
          </nuxt-link>
          <nuxt-link :to="{ name: 'companies-id-teams' }" class="nav-link">
            <img src="/assets/svgs/ic-briefcase.svg" alt="" />
            My Teams
          </nuxt-link>
          <nuxt-link :to="{ name: 'companies-id-roles' }" class="nav-link">
            <img src="/assets/svgs/ic-flag.svg" alt="" />
            Roles
          </nuxt-link>
        </div>
        <div class="flex flex-col gap-4">
          <div class="text-sm text-grey">Others</div>
          <nuxt-link to="#" class="nav-link">
            <img src="/assets/svgs/ic-box.svg" alt="" />
            Insurances
          </nuxt-link>
          <nuxt-link to="#" class="nav-link">
            <img src="/assets/svgs/ic-home.svg" alt="" />
            Company
          </nuxt-link>
          <nuxt-link to="#" class="nav-link">
            <img src="/assets/svgs/ic-gift.svg" alt="" />
            Rewards
          </nuxt-link>
          <nuxt-link to="#" class="nav-link">
            <img src="/assets/svgs/ic-settings.svg" alt="" />
            Settings
          </nuxt-link>
          <nuxt-link to="#" class="nav-link">
            <img src="/assets/svgs/ic-signout.svg" alt="" />
            Logout
          </nuxt-link>
        </div>
      </div>
    </div>
  </div>
</template>
