<template>
  <div class="bg-purple-600 w-screen h-screen">
    <div class="logo flex justify-center">
      <img src="../assets/goodvest-logo.svg" alt="Goodvest logo" class="w-28 mt-6 mb-20">
    </div>
    <div class="shadow-lg bg-white w-1/4 mx-auto rounded-md translate-y-6 overflow-hidden">
      <div class="overflow-hidden h-56">
        <img src="../assets/login-image.png" alt="illustration" class="w-full h-full object-cover"/>
      </div>
        <div class="pt-5 flex-col gap-3">
          <h1 class="font-serif italic text-center text-4xl">
            Sign in
          </h1>
        </div>
        <div class="mt-8 sm:mx-auto sm:w-full sm:max-w-md">
          <div class="bg-white pb-3.5 px-6 sm:px-10">
            <form class="mb-0 space-y-6" action="#" method="POST">
              <div>
                <label for="email" class="block text-sm font-extrabold text-gray-800 mb-2.5">Username or email</label>
                <div class="mt-1">
                  <input id="email" name="email" type="email" autocomplete="email" class="w-full border border-gray-300 px-4 py-3 rounded-sm shadow-sm focus:outline-none focus:border-indigo-500 focus:ring focus:ring-ingo-500" placeholder="Your username or email"/>
                </div>
              </div>

              <div>
                <label for="password" class="block text-sm font-extrabold text-gray-800 mb-2.5">Password</label>
                <div class="mt-1">
                  <input id="password" name="password" type="password" autocomplete="password" class="w-full border border-gray-300 px-4 py-3 rounded-sm shadow-sm focus:outline-none focus:border-indigo-500 focus:ring focus:ring-ingo-500" placeholder="Your password"/>
                </div>
                <a href="#" for="password" class="block text-xs font-extrabold text-purple-600 mt-0.5">Forgot password?</a>
              </div>
            </form>
          </div>
        </div>
      <hr class=""/>
      <div class="p-3">
        <div class="flex justify-around items-center">
          <div class="flex">
            <p class="text-xs">Don't have an account?</p> <a href="#" class="text-xs text-purple-600 ml-1">Sign up</a>
          </div>
          <div>
            <button type="button" class="py-2 px-6 border border-transparent rounded-sm shadow-sm text-sm font-bold text-white bg-purple-600 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500">Sign in</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "LoginCard"
}
</script>
