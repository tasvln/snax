<template>
    <div>
        <Nav/>
        <div class="w-full max-w-lg mx-auto my-16">
            <form class="px-8" action="">
                <p class="text-center font-bold text-4xl mb-10" style="color: #FC9604;">SNAX Developers</p>
                <input class="appearance-none border my-2 rounded-lg w-full py-4 px-4 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" placeholder="Full Name" name="Full Name" type="text">
                <input class="appearance-none border my-2 rounded-lg w-full py-4 px-4 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" placeholder="Email" type="email" name="Email" id="">
                <textarea class="appearance-none border my-2 resize-none rounded-lg w-full py-4 h-40 px-4 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" placeholder="Description of platform or app" name="Description"></textarea>
                <button style="background: rgba(252, 190, 4, 0.1); outline: none;" class="w-full rounded-lg font-bold text-gray-800 py-4">Submit</button>
            </form>
        </div>
        <br>
        <br>
        <Foot/>
    </div>
</template>