<script>
	import { fade } from 'svelte/transition';
</script>

<div class="back">
	<a href="/home">Home</a>
</div>
<div class="wrapper">
	<div class="container" in:fade={{ delay: 300, duration: 1000 }}>
		<div>
			<h1 class="title">Early Hobbies:</h1>
		</div>
		<div>
			<p>
				Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolorum sint tenetur similique,
				illo obcaecati unde deleniti asperiores quidem ipsam vero nesciunt id officia, molestias ea
				vitae nihil. Nam vel est corporis obcaecati maxime nesciunt. Itaque minima ea neque nemo
				corrupti quasi cupiditate ab ex explicabo consequuntur eum ullam unde tempore qui
				repudiandae labore, perspiciatis assumenda eveniet, nam voluptatum, excepturi eius! Dolorem
				animi laborum ipsum laudantium, voluptas illo placeat, aperiam aut eaque velit unde deleniti
				eius at exercitationem quos corrupti iusto fuga atque nulla numquam voluptate. Magni
				laudantium deleniti molestias non repudiandae officiis cupiditate a consequatur id hic,
				mollitia magnam similique.
			</p>
		</div>
	</div>
	<div class="container" in:fade={{ delay: 500, duration: 1000 }}>
		<div>
			<h1 class="title">Middle Hobbies:</h1>
		</div>
		<div>
			<p>
				Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolorum sint tenetur similique,
				illo obcaecati unde deleniti asperiores quidem ipsam vero nesciunt id officia, molestias ea
				vitae nihil. Nam vel est corporis obcaecati maxime nesciunt. Itaque minima ea neque nemo
				corrupti quasi cupiditate ab ex explicabo consequuntur eum ullam unde tempore qui
				repudiandae labore, perspiciatis assumenda eveniet, nam voluptatum, excepturi eius! Dolorem
				animi laborum ipsum laudantium, voluptas illo placeat, aperiam aut eaque velit unde deleniti
				eius at exercitationem quos corrupti iusto fuga atque nulla numquam voluptate. Magni
				laudantium deleniti molestias non repudiandae officiis cupiditate a consequatur id hic,
				mollitia magnam similique.
			</p>
		</div>
	</div>
	<div class="container" in:fade={{ delay: 700, duration: 1000 }}>
		<div>
			<h1 class="title">Present Day Hobbies:</h1>
		</div>
		<div>
			<p>
				Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolorum sint tenetur similique,
				illo obcaecati unde deleniti asperiores quidem ipsam vero nesciunt id officia, molestias ea
				vitae nihil. Nam vel est corporis obcaecati maxime nesciunt. Itaque minima ea neque nemo
				corrupti quasi cupiditate ab ex explicabo consequuntur eum ullam unde tempore qui
				repudiandae labore, perspiciatis assumenda eveniet, nam voluptatum, excepturi eius! Dolorem
				animi laborum ipsum laudantium, voluptas illo placeat, aperiam aut eaque velit unde deleniti
				eius at exercitationem quos corrupti iusto fuga atque nulla numquam voluptate. Magni
				laudantium deleniti molestias non repudiandae officiis cupiditate a consequatur id hic,
				mollitia magnam similique.
			</p>
		</div>
	</div>
</div>

<style>
	.wrapper {
		background-color: rgba(50, 50, 50, 0.3);
		border-radius: 1em;
		padding: 1em;
		width: 100dvw;
	}
	.container {
		margin: 4em auto 2em auto;
		border: 1px solid #dc400f;
		border-radius: 1em;
		padding: 1em;
		width: 90dvw;
	}
	.title {
		text-decoration: underline;
		margin-bottom: 0.2em;
	}
	.back {
		margin: 1em 0 0 1em;
	}
	a {
		text-decoration: none;
		color: red;
	}
	a:hover {
		color: #fff;
	}
</style>
