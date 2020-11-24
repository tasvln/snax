<template>
  <div>
      <Nav />
      <div class="my-6">
          <div class="my-10 mx-10">
              <p class="font-extrabold mid-text text-3xl full-width-max max-w-lg my-4">Build your Startup seemlessly without stress</p>
              <p class="italic text-lg mt-10 text-gray-600">Fill the form below to get started</p>
              <form class="max-w-2xl">
                <div class="my-6">
                    <input type="text" name="Startup Name" placeholder="Startup Name*" class="w-full py-4 px-8 rounded-lg placeholder-gray-600" style="background: rgba(252, 190, 4, 0.1);">
                </div>
                <div class="my-6">
                    <input type="text" name="Full Name" placeholder="Full Name*" class="w-full py-4 px-8 rounded-lg placeholder-gray-600" style="background: rgba(252, 190, 4, 0.1);">
                </div>
                <div class="my-6">
                    <input type="email" name="Email" placeholder="Email*" class="w-full py-4 px-8 rounded-lg placeholder-gray-600" style="background: rgba(252, 190, 4, 0.1);">
                </div>
                <div class="flex relative items-center">
                    <select name="Template" class="block appearance-none w-full py-4 px-8 rounded-lg text-gray-600" style="background: rgba(252, 190, 4, 0.1);">
                        <option selected>Choose Template*</option>
                        <option>App</option>
                        <option>App + Dashboard</option>
                    </select>
                    <div class="absolute right-0 flex items-center px-2 text-gray-800 pointer-events-none">
                        <svg class="fill-current h-4 w-4" xmlns="http://www.w3.org/2000/svg" viewB<svg class="h-5 w-5 text-gray-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true"><path fill-rule="evenodd" d="M10 3a1 1 0 01.707.293l3 3a1 1 0 01-1.414 1.414L10 5.414 7.707 7.707a1 1 0 01-1.414-1.414l3-3A1 1 0 0110 3zm-3.707 9.293a1 1 0 011.414 0L10 14.586l2.293-2.293a1 1 0 011.414 1.414l-3 3a1 1 0 01-1.414 0l-3-3a1 1 0 010-1.414z" clip-rule="evenodd" /></svg>
                    </div>
                </div>
                <div class="my-6">
                    <textarea name="Description" placeholder="Startup Description*" class="w-full py-6 px-8 rounded-lg placeholder-gray-600" style="height:350px; background: rgba(252, 190, 4, 0.1); resize: none;"></textarea>
                </div>
                <div class="my-6">
                    <button class="w-full py-4 px-8 rounded-lg font-bold text-white" style="background: #FCBE04;">Submit</button>
                </div>
              </form>
          </div>
      </div>
      <Foot />
  </div>
</template>

<style>

</style>