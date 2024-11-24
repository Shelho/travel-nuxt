<template>
  <section class="s-1">
    <div class="container">
      <div class="block">
        <div class="img">
          <img src="@/assets/images/icons/Vector_1.svg" alt="" />
        </div>
        <div>
          <h1 class="font-bold leading-70px mb-30px w-max-582px">
            No matter where you’re going to, we’ll take you there
          </h1>
        </div>
        <div
          class="rounded-11px mb-30px w-[844px] pr-27px items-stretch py-23px bg-[#F3F3F399] gap-20px flex items-center"
        >
          <div class="text-block flex w-full">
            <div class="txt">
              <h2>Where to?</h2>
            </div>
            <div class="txt">
              <h2>Travel Type</h2>
            </div>
            <div class="txt">
              <h2>Duration</h2>
            </div>
          </div>
          <div>
            <LayoutUiButton text="Submit" class="w-176px"></LayoutUiButton>
          </div>
        </div>
        <div class="flex items-center gap-15px">
          <div class="">
            <img src="@/assets/images/icons/Group_81.svg" alt="" />
          </div>
          <p>2,500 people booked Tommorowland Event in last 24 hours</p>
        </div>
      </div>
    </div>
    <div
      class="absolute bottom-[-170px] rounded-196px w-392px h-392px block-br"
    >
      <div class="block-br rounded-81px w-162px h-162px">
        <h2>scroll</h2>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.s-1 {
  @apply flex items-center bg-no-repeat bg-cover h-screen bg-logo text-white font-poppins;
}

.txt {
  @apply w-full flex items-center justify-center not-last:border-r-3;
}
h1 {
  font-size: 58px;
}
.block-br {
  @apply flex items-center justify-center border-2px border-white border-dotted bg-transparent;
}
</style>