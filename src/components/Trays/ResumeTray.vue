<template>
    <div id="resume" class="tray">
        <h1>Grab my résumé!</h1>
        <p>Take a closer look at history of my studies and work experience.</p>
        <button id="download-button">
          <h2 class="download-text">Download CV</h2>
          <img src="../../assets/icons/download.png" alt="">
        </button>
      </div>
</template>

<style>

#resume
{
    /* SIZE */
    width: 50vw;
    padding: var(--padding_m);

    /* FLEX */
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    align-items: left;
}

#download-button
{
    /* COLOR */
    background: var(--white_color);

    /* SIZE */
    width: 50%;
    height: 60%;

    /* FLEX */
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
    align-self: center;
}

#download-button:hover
{
    cursor: pointer;
}

#download-button img
{
    width: 10%;
}

#resume h1
{
    /* TEXT */
    font-size: var(--font_xl);
}

#resume h2
{
    /* TEXT */
    color: var(--back_color);
    font-size: var(--font_l);

    /* OFFSET */
    padding-left: var(--padding_m);
    padding-right: var(--padding_m);
}

</style>