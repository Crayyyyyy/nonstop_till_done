<template>
    <div id="background">
      <ProfileTray/>
      <ResumeTray/>
      <ContactTray/>
      <SkillsTray/>
      <WorkTray/>
      <CertificateTray/>
      <ScrollDogTray/>
      <ExtraTray/>
    </div>
</template>

<script>
    import CertificateTray from './Trays/CertificateTray.vue';
    import SkillsTray from './Trays/SkillsTray.vue';
    import ContactTray from './Trays/ContactTray.vue';
    import ProfileTray from './Trays/ProfileTray.vue';
    import ResumeTray from './Trays/ResumeTray.vue';
    import ScrollDogTray from './Trays/ScrollDogTray.vue';
    import WorkTray from './Trays/WorkTray.vue';
    import ExtraTray from './Trays/ExtraTray.vue';

export default {
  name: 'TrayContainer',
  components: {
    ProfileTray, ContactTray, ResumeTray, WorkTray, CertificateTray, ScrollDogTray, SkillsTray, ExtraTray  
  }
}
</script>

<style>

#background
{
    /* SIZE */
    width: 100vw;
    height: 100vh;
    max-width: var(--size_xl);
    padding: var(--padding_m);

    /* GRID */
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(5, 1fr);
    gap: 10px;
}

</style>