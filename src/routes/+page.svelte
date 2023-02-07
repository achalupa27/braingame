<div class="home">
	<div class="nav-bar">
		<div class="logo"><img src="bg_logo.png" alt="braingame logo" /></div>
		<div class="site">
			<div><a href="/energy">Energy</a></div>
			<div><a href="/focus">Focus</a></div>
			<div><a href="/sleep">Sleep</a></div>
			<div><a href="/mood">Mood</a></div>
			<div class="shop-box"><span class="shop">Shop</span></div>
		</div>
		<div class="sign-in">Sign In</div>
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
    a
        color: inherit
        text-decoration: none

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

        &:hover
            cursor: pointer
            filter: drop-shadow(0 0 1rem white)

    .site
        display: flex
        align-items: center
        gap: 24px

        div
            &:hover
                cursor: pointer
                filter: drop-shadow(0 0 0.5rem white)
            
        .shop-box
            height: 32px
            width: 64px
            background-image: linear-gradient(45deg, #fdb0c7, #c5cbe6)
            border: 1px solid pink
            display: flex
            align-items: center
            justify-content: center
            border-radius: 6px

        .shop
            font-family: 'Poppins'
            font-size: 14px
            font-weight: 600
            color: white
            text-shadow: -1px -1px 0 pink, 1px -1px 0 pink, -1px 1px 0 pink, 1px 1px 0 pink


    .sign-in
        margin-right: 12px

    .center
        height: calc(100% - 68px)
        display: flex
        justify-content: center
        align-items: center
        flex-direction: column

    .center-content

        .center-main
            font-size: 92px
            line-height: 70px
            filter: drop-shadow(0 0 0.4rem white)
            text-shadow: 0 2px 4px grey

        .center-sub
            font-size: 36px
            margin-left: 4px
            text-shadow: 0 2px 4px grey

    .get-started
        cursor: pointer
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
        filter: drop-shadow(0 4px 4px grey)

        &:hover
            filter: drop-shadow(0 0 1.5rem white)


</style>
