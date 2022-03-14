<template>
        <div
      class="min-h-screen grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-1"
    >
      <div class="flex flex-row m-3 subtitle justify-center">
        <h2 class="">Education</h2>
      </div>
      <div class="flex flex-row m-3 subtitle justify-center">
        <h2 class="">Tech Skills</h2>
      </div>
      <div class="flex flex-row m-3 subtitle justify-center">
        <h2 class="">Work Experience</h2>
      </div>
      <div class="flex flex-row m-3 subtitle justify-center">
        <h2 class="">Soft Skills</h2>
      </div>

      <div class="flex flex-row m-3 subtitle justify-center">
        <h2 class="">Aditional Education</h2>
      </div>
      <div class="flex flex-row m-3 subtitle justify-center">
        <h2 class="">Certifications</h2>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'QualificationsComponent',
}
</script>

<style>
.subtitle {
  @apply font-semibold text-xl text-yellow-300 text-center;
}
</style>
