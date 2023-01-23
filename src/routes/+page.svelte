<div class="home">
	<div class="nav-bar">
		<div class="logo"><img src="bg_logo.png" alt="braingame logo" /></div>
		<div class="site">
			<div>Energy</div>
			<div>Focus</div>
			<div>Sleep</div>
			<div>Mood</div>
			<div class="shop">Shop</div>
		</div>
		<div>Sign In</div>
	</div>
	<div class="center">
		<div class="center-content">
			<div class="center-main">BRAINGAME</div>
			<div class="center-sub">The Leaders in Brain Optimization</div>
		</div>
		<div class="get-started">Get Started</div>
	</div>
</div>

<style lang="sass">
    .home
        background-image: url('/bg_bg.png')
        height: 100%
        font-family: 'Varela Round'
        color: white

    .nav-bar
        display: flex
        justify-content: space-between
        align-items: center
        padding: 6px 18px

    .logo img
        width: 50px
        height: 50px

    .site
        display: flex
        gap: 24px

    .center
        height: calc(100% - 68px)
        display: flex
        justify-content: center
        align-items: center
        flex-direction: column

    .center-content

        .center-main
            font-size: 92px
            line-height: 66px

        .center-sub
            font-size: 36px
            margin-left: 4px

    .get-started
        position: relative
        display: flex
        align-items: center
        justify-content: center
        top: 160px
        width: 200px
        height: 42px
        background: white
        color: #8895cf
        border-radius: 18px

</style>
