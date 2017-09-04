# SovietDiscord

//META{"name":"ClearVision_Ruby","description":"A raging, red theme with customizable colors & background!</br> Based on <a href='https://github.com/0mniscient/Discord-Themes/tree/master/Themes' target='_blank'>Discord Reborn</a> by <a href='https://github.com/0mniscient' target='_blank'>@Omniscient</a> & <a href='https://github.com/cosmicsalad/Discord-Themes-and-Plugins/tree/master/themes/DarkMatter' target='_blank'>DarkMatter</a> by <a href='https://github.com/cosmicsalad' target='_blank'>@Hammock</a> <span style='position: absolute; bottom: 0; left: 0;'>Links: <b><a href='https://git.io/v6BHO' target='_blank'>Github</a></b> | <b><a href='https://discord.gg/FtYVPky' target='_blank'>Discord</a></b> | <b><a href='https://git.io/vXTqM' target='_blank'>Wiki</a></b></span> <span style='position: absolute; bottom: 0; right: 14px;'>By <b><a href='https://github.com/Zerthox' target='_blank'>@Zerthox</a></b></span>","author":"<a href='https://github.com/Zerthox' target='_blank'>@Zerthox</a>","version":"5"}*//{}
/* "ClearVision - Ruby v5" by @Zerthox */
/* Based on "Discord Reborn v4.30" by @Omniscient & "DarkMatter" by @Hammock */

/* IMPORT CSS FROM GITHUB */
@import url(https://gitcdn.xyz/repo/Zerthox/ClearVision/master/css/ClearVision_v5.min.css);
/*
---------------------------------------------------------------------------------------------------------------------------------------------
IMPORTANT: CHANGE BETWEEN DARK AND LIGHT VERSION IN APPEARANCE SETTINGS!
---------------------------------------------------------------------------------------------------------------------------------------------
*/
/*
---------------------------------------------------------------------------------------------------------------------------------------------
*/
/*
---------------------------------------------------------------------------------------------------------------------------------------------
============== CUSTOMIZABLE COLORS ===============
*/
:root {
	--main-color: #e62727;
	--hover-color: #b31e1e;
    --background-blur: 0px;
    --background-brightness: 100%;
}
/*
--------------------------------------------------------------------------------------------------------------------------------------------
*/
/*
---------------------------------------------------------------------------------------------------------------------------------------------
========= CUSTOMIZABLE BACKGROUND IMAGE ==========
*/
body::after,
.callout-backdrop,
.user-popout::before,
#user-profile-modal .header::before,
#pubs-container::before,
.auth-background,
.auth-tiling-bg,
.invite-modal .invite-splash,
.radio-theme.light label,
.radio-theme.dark label{
    background-image: url(https://imgur.com/a/CeelO) !important; /* IMPORTANT: Link must be HTTPS! */
}
/*
--------------------------------------------------------------------------------------------------------------------------------------------
*/
