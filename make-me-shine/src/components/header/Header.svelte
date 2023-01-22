<script>
   import { Lightbox } from 'svelte-lightbox'
    import ProfilePic from "$lib/profile-picture.jpeg"
</script>

<div class="w-full h-full flex flex-col justify-between">

    <header class="h-16 w-full flex items-center relative justify-end px-5 space-x-10 bg-gray-800">
      <div class="flex flex-shrink-0 items-center space-x-4 text-white">
        
        <div class="flex flex-col items-end ">
          <div class="text-md font-medium ">FARZAM MOHAMMADI</div>
          <div class="text-sm font-regular">Full-Stack Developer</div>
        </div>
        <!-- Profile photo -->
        <Lightbox description="Tis I">
          <img class="h-12 w-12 rounded-full cursor-pointer bg-gray-200 border-2 border-blue-400" src={ProfilePic} alt="Profile"/>
        </Lightbox>
      </div>
    </header>
</div>