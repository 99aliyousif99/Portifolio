Users\aljan\Desktop\Portifolio\src\components\Contact.vue
<script>
export default {};
</script>

<template>
  <section class="bg-transparent mt-10 sm:mt-15 lg:mt-20 px-4 lg:px-0">
    <div class="mx-auto max-w-screen-md">
      <h2 class="mb-4 text-3xl sm:text-4xl md:text-5xl lg:text-6xl tracking-tight font-extrabold text-[#ff0022] text-center lg:text-left">Contact</h2>
      <form action="#" class="space-y-6 sm:space-y-8">
        <div>
          <label for="email" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Your email</label>
          <input type="email" id="email" class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-500 focus:border-primary-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500 dark:shadow-sm-light" placeholder="name@flowbite.com" required>
        </div>
        <div>
          <label for="subject" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Subject</label>
          <input type="text" id="subject" class="block p-3 w-full text-sm text-gray-900 bg-gray-50 rounded-lg border border-gray-300 shadow-sm focus:ring-primary-500 focus:border-primary-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500 dark:shadow-sm-light" placeholder="Let us know how we can help you" required>
        </div>
        <div class="sm:col-span-2">
          <label for="message" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-400">Your message</label>
          <textarea id="message" rows="6" class="block p-2.5 w-full text-sm text-gray-900 bg-gray-50 rounded-lg shadow-sm border border-gray-300 focus:ring-primary-500 focus:border-primary-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="Leave a comment..."></textarea>
        </div>
        <button type="submit" class="py-3 px-5 text-sm font-medium text-center text-white rounded-lg bg-[#B91372] w-full sm:w-fit hover:bg-[#9A1062] focus:ring-4 focus:outline-none focus:ring-primary-300 transition-colors duration-300">Send message</button>
      </form>
    </div>
  </section>
</template>