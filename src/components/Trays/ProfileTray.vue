<template>
    <div class="tray" id="profile">
      <div class="photo"><img src="../../assets/photos/profile-cropped.png" alt="MeMyself&I.jpg"></div>
      <h2 class="name">Bc. Róbert Plávka</h2>
      <div class="stats">
        <div>
          <span><h3>Age</h3></span>
          <h4>23</h4>
        </div>
        <div>
        <span><h3>Field</h3></span>
          <h4>IT</h4>
        </div>
        <div>
        <span><h3>Status</h3></span>
          <h4>Ready!</h4>
        </div>
      </div>

      <div class="back-red"></div>   
    </div>
</template>

<style scoped>

  h3
  {
    color: crimson
  }

  #profile
  {
    @apply row-span-2 p-0;

    background: linear-gradient(to top, var(--tray_color) 68%, crimson 50%);
    /* FLEX */
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    align-items: center;
  }

  .stats
  {
    /* FLEX */
    display: flex;
    justify-content: space-around;
    width: 100%;
  }

  .stats > *
  {
    /* FLEX */
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  .photo
  {
    /* FLEX */
    display: flex;
    justify-content: center;
    align-items: center
  }

  img
  {
    @apply rounded-[50%] w-[75%];
    border-bottom: var(--border_light);
    box-sizing: border-box;
  }

</style>