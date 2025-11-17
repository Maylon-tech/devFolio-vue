<template lang="">
    <div id="contact" class="flex flex-col gap-5 justify-center items-center">

        <div class="flex flex-col justify-center items-start bg-[url('/public/assets/terminal.png')] bg-center bg-contain bg-no-repeat h-[800px] p-32 w-4/5">
            <h1 class="text-3xl font-bold text-gray-300 w-full pb-4">Let's Talk</h1>
            <p class="text-gray-500 text-sm">
                Our team is here to help you with your project needs. Contact us today. 
            </p>

            <div class="flex flex-col gap-6 my-4 w-full">
                <div class="text-gray-500">Full Name</div>
                <input
                  type="text"
                  class="w-full border-b border-gray-500 bg-gray-900 p-3 rounded-lg"
                  placeholder="John Doe"
                />
            </div>

            <div class="flex flex-col gap-4 my-4 w-full">
                <div class="text-gray-500">Email Address</div>
                <input
                  type="email"
                  class="w-full border-b border-gray-500 bg-gray-900 p-3 rounded-lg"
                  placeholder="Johndoe@hotmail.com"
                />
            </div>

            <div class="flex flex-col gap-4 my-4 w-full border-0">
                <div class="text-gray-500">Your Message</div>
                <textarea
                  type="text"
                  class="w-full border-b border-gray-500 bg-gray-900 p-3 rounded-lg resize-none h-20"
                  placeholder="Your Comment"
                />
            </div>

            <button 
                class="w-full p-2 rounded-lg bg-gray-800 hover:bg-gray-600 transition-all cursor-pointer mt-2"
            >
                Send Message
            </button>
        </div> 
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="">
    
</style>