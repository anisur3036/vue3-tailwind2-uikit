<template>
	<div
      class="layout relative overflow-hidden min-h-full flex"
      style="padding-top: 52px"
    >
      <div
        class="header z-10 fixed top-0 left-0 right-0 flex items-center justify-between bg-indigo-900 px-2"
      >
        <div class="w-[256px]">
          <a class="flex items-center text-gray-100" href="#">
            <svg
              class="w-6 h-6"
              fill="currentColor"
              viewBox="0 0 20 20"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                d="M12 7a1 1 0 110-2h5a1 1 0 011 1v5a1 1 0 11-2 0V8.414l-4.293 4.293a1 1 0 01-1.414 0L8 10.414l-4.293 4.293a1 1 0 01-1.414-1.414l5-5a1 1 0 011.414 0L11 10.586 14.586 7H12z"
                clip-rule="evenodd"
              ></path>
            </svg>
            <span class="font-semibold text-xl">CRM Design</span>
          </a>
        </div>
        <div class="header__right hidden sm:flex sm:flex-1 sm:items-center sm:justify-between">
          <form class="inline-block w-full items-center relative" action="">
            <button
              class="absolute inset-0 pl-2 border-transparent focus:outline-none"
            >
              <svg
                class="w-5 h-5 text-indigo-900"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
                ></path>
              </svg>
            </button>
            <input
              class="w-[87%] pl-8 py-1 bg-[#1D1B4D] text-gray-200 rounded-md border-transparent shadow-inner"
              type="text"
              placeholder="search"
            />
          </form>
          <div class="flex items-center">
            <button class="mr-2">
              <svg
                class="w-6 h-6 text-gray-300"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"
                />
              </svg>
            </button>
            <button
              class="flex items-center w-[150px] focus:outline-none py-3 border-l-2 border-indigo-dark"
            >
              <span class="text-white px-3 text-right overflow-hidden">Brando</span>
              <img
                class="w-7 h-7 rounded-full object-cover"
                src="https://avatars.githubusercontent.com/u/5952472?v=4"
                alt=""
              />
            </button>
          </div>
        </div>
      </div>
      <div class="flex relative">
        <div
          class="relative sm:left-[256px] ml-6 pb-6 pt-4 sm:pr-[256px] min-w-[320px] z-0 order-1 flex-1 min-h-full"
        >
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptate eveniet, excepturi numquam similique odit voluptatem temporibus. Odio autem provident recusandae quo eos, ipsum, doloribus earum dignissimos, nisi unde quisquam dolorum!
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptate eveniet, excepturi numquam similique odit voluptatem temporibus. Odio autem provident recusandae quo eos, ipsum, doloribus earum dignissimos, nisi unde quisquam dolorum!
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptate eveniet, excepturi numquam similique odit voluptatem temporibus. Odio autem provident recusandae quo eos, ipsum, doloribus earum dignissimos, nisi unde quisquam dolorum!
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptate eveniet, excepturi numquam similique odit voluptatem temporibus. Odio autem provident recusandae quo eos, ipsum, doloribus earum dignissimos, nisi unde quisquam dolorum!
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptate eveniet, excepturi numquam similique odit voluptatem temporibus. Odio autem provident recusandae quo eos, ipsum, doloribus earum dignissimos, nisi unde quisquam dolorum!
        </div>
        <div class="z-0 bg-gray-50 border-r border-gray-200">
  <div
    class="hidden sm:block sidebar w-[256px] pt-8 h-full fixed top-14 overflow-x-hidden left-0 overflow-y-scroll"
  >
    <div
      class="sidebar-heading pb-2 px-4 font-semibold uppercase text-xs text-gray-400 tracking-[0.92px] leading-normal"
    >
      Menu
    </div>
    <ul class="mb-4 p-0">
      <li class="relative dropdown-container overflow-hidden" @click="submenu = !submenu">
        <a
          class="header dashboard text-purple-600 py-0 px-4 flex items-center text-sm font-medium leading-10 transition-colors duration-300 ease-in-out"
          href="#"
        >
          <svg
            class="w-6 h-6"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
            ></path>
          </svg>
          <span class="flex-1 pl-2">Dashboards</span>
          <svg
            class="w-6 h-6 text-gray-400"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 9v3m0 0v3m0-3h3m-3 0H9m12 0a9 9 0 11-18 0 9 9 0 0118 0z"
            ></path>
          </svg>
        </a>
        <article v-show="submenu === true">
          <div class="article-inner">
            <ul class="pl-12">
              <li class="py-1"><a href="#">submenu list 1</a></li>
              <li class="py-1"><a href="#">submenu list 2</a></li>
              <li class="py-1"><a href="#">submenu list 3</a></li>
              <li class="py-1"><a href="#">submenu list 4</a></li>
              <li class="py-1"><a href="#">submenu list 5</a></li>
            </ul>
          </div>
        </article>
      </li>
      <li class="relative dropdown-container overflow-hidden">
        <a
          class="header text-gray-600 py-0 px-4 flex items-center text-sm font-medium leading-10"
          href=""
        >
          <svg
            class="w-6 h-6 text-gray-400"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M11 3.055A9.001 9.001 0 1020.945 13H11V3.055z"
            ></path>
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M20.488 9H15V3.512A9.025 9.025 0 0120.488 9z"
            ></path>
          </svg>
          <span class="flex-1 pl-2">Apps</span>
          <svg
            class="w-6 h-6 text-gray-400"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 9v3m0 0v3m0-3h3m-3 0H9m12 0a9 9 0 11-18 0 9 9 0 0118 0z"
            ></path>
          </svg>
        </a>
        <ul class="hidden">
          <li><a href="#">submenu list 1</a></li>
          <li><a href="#">submenu list 2</a></li>
          <li><a href="#">submenu list 3</a></li>
          <li><a href="#">submenu list 4</a></li>
          <li><a href="#">submenu list 5</a></li>
        </ul>
      </li>
      <li class="relative overflow-hidden">
        <a
          class="py-0 px-4 text-gray-600 flex items-center text-sm font-medium leading-10"
          href=""
        >
          <svg
            class="w-6 h-6 text-gray-400"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M17 9V7a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2m2 4h10a2 2 0 002-2v-6a2 2 0 00-2-2H9a2 2 0 00-2 2v6a2 2 0 002 2zm7-5a2 2 0 11-4 0 2 2 0 014 0z"
            ></path>
          </svg>
          <span class="flex-1 pl-2">Camera</span>
          <svg
            class="w-6 h-6 text-gray-400"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 9v3m0 0v3m0-3h3m-3 0H9m12 0a9 9 0 11-18 0 9 9 0 0118 0z"
            ></path>
          </svg>
        </a>
      </li>
      <li class="relative overflow-hidden">
        <a
          class="py-0 px-4 text-gray-600 flex items-center text-sm font-medium leading-10"
          href=""
        >
          <svg
            class="w-6 h-6 text-gray-400"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M3 9a2 2 0 012-2h.93a2 2 0 001.664-.89l.812-1.22A2 2 0 0110.07 4h3.86a2 2 0 011.664.89l.812 1.22A2 2 0 0018.07 7H19a2 2 0 012 2v9a2 2 0 01-2 2H5a2 2 0 01-2-2V9z"
            ></path>
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M15 13a3 3 0 11-6 0 3 3 0 016 0z"
            ></path>
          </svg>
          <span class="flex-1 pl-2">Pages</span>
          <svg
            class="w-6 h-6 text-gray-400"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 9v3m0 0v3m0-3h3m-3 0H9m12 0a9 9 0 11-18 0 9 9 0 0118 0z"
            ></path>
          </svg>
        </a>
        <ul class="hidden">
          <li><a href="#">submenu list 1</a></li>
          <li><a href="#">submenu list 2</a></li>
          <li><a href="#">submenu list 3</a></li>
          <li><a href="#">submenu list 4</a></li>
          <li><a href="#">submenu list 5</a></li>
        </ul>
      </li>
      <li class="relative overflow-hidden">
        <a
          class="py-0 px-4 text-gray-600 flex items-center text-sm font-medium leading-10"
          href=""
        >
          <svg
            class="w-6 h-6 text-gray-400"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"
            ></path>
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
            ></path>
          </svg>
          <span class="flex-1 pl-2">Loaders</span>
        </a>
      </li>
    </ul>
    <div
      class="sidebar-heading pb-2 px-4 font-semibold uppercase text-xs text-gray-400 tracking-[0.92px] leading-normal"
    >
      Menu
    </div>
    <ul class="mb-4 p-0">
      <li class="relative overflow-hidden">
        <a
          class="text-gray-600 py-0 px-4 flex items-center text-sm font-medium leading-10"
          href=""
        >
          <svg
            class="w-6 h-6"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
            ></path>
          </svg>
          <span class="flex-1 pl-2">Dashboards</span>
        </a>
      </li>
      <li class="relative overflow-hidden">
        <a
          class="text-gray-600 py-0 px-4 flex items-center text-sm font-medium leading-10"
          href=""
        >
          <svg
            class="w-6 h-6"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
            ></path>
          </svg>
          <span class="flex-1 pl-2">Dashboards</span>
        </a>
      </li>
      <li class="relative overflow-hidden">
        <a
          class="text-gray-600 py-0 px-4 flex items-center text-sm font-medium leading-10"
          href=""
        >
          <svg
            class="w-6 h-6"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
            ></path>
          </svg>
          <span class="flex-1 pl-2">Dashboards</span>
        </a>
      </li>
      <li class="relative overflow-hidden">
        <a
          class="text-gray-600 py-0 px-4 flex items-center text-sm font-medium leading-10"
          href=""
        >
          <svg
            class="w-6 h-6"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
            ></path>
          </svg>
          <span class="flex-1 pl-2">Dashboards</span>
        </a>
      </li>
      <li class="relative overflow-hidden">
        <a
          class="text-gray-600 py-0 px-4 flex items-center text-sm font-medium leading-10"
          href=""
        >
          <svg
            class="w-6 h-6"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
            ></path>
          </svg>
          <span class="flex-1 pl-2">Dashboards</span>
        </a>
      </li>
      <li class="relative overflow-hidden">
        <a
          class="text-gray-600 py-0 px-4 flex items-center text-sm font-medium leading-10"
          href=""
        >
          <svg
            class="w-6 h-6"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
            ></path>
          </svg>
          <span class="flex-1 pl-2">Dashboards</span>
        </a>
      </li>
      <li class="relative overflow-hidden">
        <a
          class="text-gray-600 py-0 px-4 flex items-center text-sm font-medium leading-10"
          href=""
        >
          <svg
            class="w-6 h-6"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
            ></path>
          </svg>
          <span class="flex-1 pl-2">Dashboards</span>
        </a>
      </li>
      <li class="relative overflow-hidden">
        <a
          class="text-gray-600 py-0 px-4 flex items-center text-sm font-medium leading-10"
          href=""
        >
          <svg
            class="w-6 h-6"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
            ></path>
          </svg>
          <span class="flex-1 pl-2">Dashboards</span>
        </a>
      </li>
      <li class="relative overflow-hidden">
        <a
          class="text-gray-600 py-0 px-4 flex items-center text-sm font-medium leading-10"
          href=""
        >
          <svg
            class="w-6 h-6"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
            ></path>
          </svg>
          <span class="flex-1 pl-2">Dashboards</span>
        </a>
      </li>
      <li class="relative overflow-hidden">
        <a
          class="text-gray-600 py-0 px-4 flex items-center text-sm font-medium leading-10"
          href=""
        >
          <svg
            class="w-6 h-6"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
            ></path>
          </svg>
          <span class="flex-1 pl-2">Dashboards</span>
        </a>
      </li>
      <li class="relative overflow-hidden">
        <a
          class="text-gray-600 py-0 px-4 flex items-center text-sm font-medium leading-10"
          href=""
        >
          <svg
            class="w-6 h-6"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
            ></path>
          </svg>
          <span class="flex-1 pl-2">Dashboards</span>
        </a>
      </li>
    </ul>
  </div>
</div>
      </div>
    </div>
</template>

<script>
	export default {
		data() {
			return {
				submenu: false
			}
		}
	}
</script>