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
			<p>My first main love was music. I taught myself how to play guitar, and to write songs.</p>
			<p>
				By the time I was living in upstate New York I had gotten pretty good. I joined my brother's
				band where we played all over upstate New York on the weekends, doing cover songs.
			</p>
			<p>
				I had also at the same time formed a band with a few of my friends. We did all original
				material. We wrote all of our songs together and even did a little recording.
			</p>
			<p>
				We had developed quite a little following for such a small time band, but hey we had lot's
				of fun, along with some small success.
			</p>
		</div>
	</div>
	<div class="container" in:fade={{ delay: 500, duration: 1000 }}>
		<div>
			<h1 class="title">Middle Hobbies:</h1>
		</div>
		<div>
			<p>
				I continued down the path of music, and to this day I am still on that path. I kept on
				practicing and learning. I taught myself how to play the drums, bass and piano.
			</p>
			<p>
				During these times I learned all about recording. Mixing and Mastering tracks. I grew very
				competent using my DAW. I would record quite a bit of music.
			</p>
			<p>
				I began to get into composing more music, instrumentals. I gained some success with these,
				having a few of my tracks placed in various media outlets.
			</p>
			<p>
				During these times, I found myself on online radio, and even had two different tracks placed
				on two seperate compilation albums through Moiko Record Company. Which can still be found on
				Amazon.
			</p>
			<p>My passion for learning never ceases, and I ventured into the world of photography.</p>
			<p>
				I started with astrophotography, as I love space and astronomy. From there I moved into
				landscape, portrait, and corporate head shot photography. I've done several corporate
				shoots, senior portraits and some product photography.
			</p>
			<p>
				So in learning photography skills, I also had to learn editing skills. I put my passion for
				learning into high gear to learn Adobe Photoshop, as well as Adobe Premiere Pro for video
				editing.
			</p>
			<p>
				With the videography skills and editing under my belt, I put together several commercials
				for my property maintenance company.
			</p>
		</div>
	</div>
	<div class="container" in:fade={{ delay: 700, duration: 1000 }}>
		<div>
			<h1 class="title">Present Day Hobbies:</h1>
		</div>
		<div>
			<p>
				Currently I still enjoy writing, recording and playing music. Photography and videography
				are still a big part of my life, as I love creating.
			</p>
			<p>
				I pursue learning more about coding everyday. I keep writing code, and taking more courses.
				I thrive in learning, as I believe if you are not learning, you are not growing. Constant
				self improvement is a necessity to me.
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
