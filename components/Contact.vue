<template>
  <section id="contact" class="flex flex-col gap-2">
    <SectionTitle> Wanna get in touch? </SectionTitle>

    <p class="text-xl text-black-primary dark:text-white-primary">
      I am always available for exciting opportunities, questions, or just a chat.
    </p>

    <div>
      <div class="my-2 flex items-center gap-2">
        <IconsEmail height="20" width="20" />

        <a class="text-xl text-black-primary underline dark:text-white-primary"
          href="mailto:felix.montanari@proton.me">felix.montanari@proton.me</a>
      </div>

      <div class="mb-4 flex items-center gap-2">
        <IconsPin height="20" width="20" />

        <p class="text-xl text-black-primary dark:text-white-primary">
          Sydney, Australia
        </p>
      </div>
    </div>

    <div class="flex gap-4">
      <GithubLink />

      <LinkedInLink />
    </div>
  </section>
</template>
