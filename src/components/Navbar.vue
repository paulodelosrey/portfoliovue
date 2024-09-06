<template>
<div class="navbar bg-base-100">
  <div class="flex-1">
    <a class="btn btn-ghost text-xl">paulo.porfolio()</a>
  </div>
  <div class="flex-none">
    <div class="dropdown dropdown-end">
      <div
        tabindex="0"
        class="card card-compact dropdown-content bg-base-100 z-[1] mt-3 w-52 shadow"
      >
      </div>
    </div>
    <div class="dropdown dropdown-end">
      <div tabindex="0" role="button" class="btn btn-ghost btn-circle avatar">
        <div class="w-10 rounded-full">
          <img
            alt="Tailwind CSS Navbar component"
            src="/me.png"
          />
        </div>
      </div>
    </div>
  </div>
</div>

</template>

<script>
export default {
    name: 'Navbar',
}
</script>

