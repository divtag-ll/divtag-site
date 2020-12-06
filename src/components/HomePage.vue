<template>
  <div class="relative bg-white overflow-hidden">
    <div class="max-w-7xl mx-auto">
      <div class="relative z-10 pb-8 bg-white sm:pb-16 md:pb-20 lg:max-w-2xl lg:w-full lg:pb-28 xl:pb-32">
        <svg class="hidden lg:block absolute right-0 inset-y-0 h-full w-48 text-white transform translate-x-1/2" fill="currentColor" viewBox="0 0 100 100" preserveAspectRatio="none" aria-hidden="true">
          <polygon points="50,0 100,0 50,100 0,100" />
        </svg>

        <div class="relative pt-6 px-4 sm:px-6 lg:px-8">
          <nav class="relative flex items-center justify-between sm:h-10 lg:justify-start" aria-label="Global">
            <div class="hidden md:block md:ml-10 md:pr-4 md:space-x-8">
              <a href="#" class="font-medium text-green-600 hover:text-green-500">FAQ</a>
              <!-- <a href="#" class="font-medium text-gray-500 hover:text-gray-900">Docs</a>-->
            </div>
          </nav>
        </div>

        <main class="mt-10 mx-auto max-w-7xl px-4 sm:mt-12 sm:px-6 md:mt-16 lg:mt-20 lg:px-8 xl:mt-28">
          <div class="sm:text-center lg:text-left">
            <h1 class="text-4xl tracking-tight font-extrabold text-gray-900 sm:text-5xl md:text-6xl">
              <span class="block xl:inline">DivTag</span>
              <span class="block text-green-700 xl:inline"> Web Developers</span>
            </h1>
            <p class="mt-3 text-base text-gray-500 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0">
               A Meetup of Web Developers of all experiences and all career levels. Join if you would like to learn more, give talks or just mingle with other like-minded Developers in Lilongwe.
            </p>
            <div class="mt-5 sm:mt-8 sm:flex sm:justify-center lg:justify-start">
              <div class="rounded-md shadow">
                <a href="#" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-md text-white bg-green-800 hover:bg-green-900 md:py-4 md:text-lg md:px-10">
                  Join the Community
                </a>
              </div>
            </div>
          </div>
        </main>
      </div>
    </div>
    <div class="lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2">
      <img class="h-56 w-full object-cover sm:h-72 md:h-96 lg:w-full lg:h-full" src="../assets/bg.jpg" alt="">
    </div>
  </div>
  <br>
  <div class="relative bg-white overflow-hidden">
    <h2 class="text-base text-green-700 font-semibold tracking-wide uppercase">
      1st Meeting
    </h2>
    <p>
      Our first meeting took place at mHUB offices, Lilongwe, Malawi, on Sunday, 4th February, 2018, with more meetings taking place every last Sunday of the month.
    </p>
  </div>
  <!-- This example requires Tailwind CSS v2.0+ -->
  <div class="py-12 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="lg:text-center">
        <h2 class="text-base text-green-700 font-semibold tracking-wide uppercase">
          The DivTag Microservice/ API EcoSystem
        </h2>
        <p class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl">
          An integrative way to deliver in the development industry
        </p>
        <p class="lg:mx-auto">
          Within DivTag, every member can contribute to any of the services that exist within the EcoSystem for DivTag.
        </p>
      </div>

      <div class="mt-10">
        <dl class="space-y-10 md:space-y-0 md:grid md:grid-cols-2 md:gap-x-8 md:gap-y-10">
          <div class="flex">
            <div class="flex-shrink-0">
              <div class="flex items-center justify-center h-12 w-12 rounded-md bg-green-600 text-white">
                <!-- Heroicon name: globe-alt -->
                <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9" />
                </svg>
              </div>
            </div>
            <div class="ml-4">
              <dt class="text-lg leading-6 font-medium text-gray-900">
                Blog Service
              </dt>
              <dd class="mt-2 text-base text-gray-500">
                GET | POST | UPDATE | DESTROY blog endpoints.
              </dd>
            </div>
          </div>

          <div class="flex">
            <div class="flex-shrink-0">
              <div class="flex items-center justify-center h-12 w-12 rounded-md bg-green-600 text-white">
                <!-- Heroicon name: scale -->
                <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 6l3 1m0 0l-3 9a5.002 5.002 0 006.001 0M6 7l3 9M6 7l6-2m6 2l3-1m-3 1l-3 9a5.002 5.002 0 006.001 0M18 7l3 9m-3-9l-6-2m0-2v2m0 16V5m0 16H9m3 0h3" />
                </svg>
              </div>
            </div>
            <div class="ml-4">
              <dt class="text-lg leading-6 font-medium text-gray-900">
                Events Service
              </dt>
              <dd class="mt-2 text-base text-gray-500">
                GET | POST | UPDATE | DESTROY events endpoints
              </dd>
            </div>
          </div>

          <div class="flex">
            <div class="flex-shrink-0">
              <div class="flex items-center justify-center h-12 w-12 rounded-md bg-green-600 text-white">
                <!-- Heroicon name: lightning-bolt -->
                <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
                </svg>
              </div>
            </div>
            <div class="ml-4">
              <dt class="text-lg leading-6 font-medium text-gray-900">
                Member Service
              </dt>
              <dd class="mt-2 text-base text-gray-500">
                GET | POST | UPDATE | DESTROY member endpoints
              </dd>
            </div>
          </div>

          <div class="flex">
            <div class="flex-shrink-0">
              <div class="flex items-center justify-center h-12 w-12 rounded-md bg-green-600 text-white">
                <!-- Heroicon name: annotation -->
                <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z" />
                </svg>
              </div>
            </div>
            <div class="ml-4">
              <dt class="text-lg leading-6 font-medium text-gray-900">
                Showcase Service
              </dt>
              <dd class="mt-2 text-base text-gray-500">
                GET | POST | UPDATE | DESTROY showcase endpoints
              </dd>
            </div>
          </div>

        </dl>
      </div>
    </div>
  </div>


<!--    <h3>How to contribute to our code</h3>-->
<!--      <a href="https://github.com/divtag-ll/divtag-site" target="_blank" rel="noopener">https://github.com/divtag-ll/divtag-site</a>.-->

<!--    <br>-->
<!--    <p class="m1-txt1 p-b-36">-->
<!--      Our next event is <span class="m1-txt2">Coming Soon</span>, follow us for an update here!-->
<!--    </p>-->

<!--    <br>-->
<!--    <div class="flex ...">-->
<!--      <div class="flex-auto rounded-xl shadow-md overflow-hidden">-->
<!--        &lt;!&ndash; Will grow and shrink as needed taking initial size into account &ndash;&gt;-->
<!--        <div class="md:flex">-->
<!--          <div class="md:flex-shrink-0">-->
<!--            <span></span>-->
<!--          </div>-->
<!--          <div class="p-8">-->
<!--            <div class="uppercase tracking-wide text-sm text-indigo-500 font-semibold">Events Service</div>-->
<!--            <a href="#" class="block mt-1 text-lg leading-tight font-medium text-black hover:underline">-->
<!--              Requesting/ Receiving from the Blog service-->
<!--            </a>-->
<!--            <p class="mt-2 text-gray-500">-->
<!--              Requesting/ Receiving from the Blog service-->
<!--            </p>-->
<!--          </div>-->
<!--        </div>-->
<!--      </div>-->
<!--      <div class="flex-auto rounded-xl shadow-md overflow-hidden">-->
<!--        &lt;!&ndash; Will grow and shrink as needed taking initial size into account &ndash;&gt;-->
<!--        <div class="md:flex">-->
<!--          <div class="md:flex-shrink-0">-->
<!--            <span></span>-->
<!--          </div>-->
<!--          <div class="p-8">-->
<!--            <div class="uppercase tracking-wide text-sm text-indigo-500 font-semibold">Member Service</div>-->
<!--            <a href="#" class="block mt-1 text-lg leading-tight font-medium text-black hover:underline">-->
<!--              Requesting/ Receiving from the Blog service-->
<!--            </a>-->
<!--            <p class="mt-2 text-gray-500">-->
<!--              Requesting/ Receiving from the Blog service-->
<!--            </p>-->
<!--          </div>-->
<!--        </div>-->
<!--      </div>-->
<!--      <div class="flex-auto rounded-xl shadow-md overflow-hidden">-->
<!--        &lt;!&ndash; Will grow and shrink as needed taking initial size into account &ndash;&gt;-->
<!--        <div class="md:flex">-->
<!--          <div class="md:flex-shrink-0">-->
<!--            <span></span>-->
<!--          </div>-->
<!--          <div class="p-8">-->
<!--            <div class="uppercase tracking-wide text-sm text-indigo-500 font-semibold">Blog Service</div>-->
<!--            <a href="#" class="block mt-1 text-lg leading-tight font-medium text-black hover:underline">-->
<!--              Requesting/ Receiving from the Blog service-->
<!--            </a>-->
<!--            <p class="mt-2 text-gray-500">-->
<!--              Requesting/ Receiving from the Blog service-->
<!--            </p>-->
<!--          </div>-->
<!--        </div>-->
<!--      </div>-->
<!--    </div>-->
<!--    <br>-->
<!--    <br>-->
<!--    <MemberList/>-->


<!--  </div>-->
</template>

<script>
// import MemberList from "@/components/MemberService/MemberList";
export default {
  name: 'HomePage',
  components: {},
  props: {
    msg: String
  }
}
</script>
