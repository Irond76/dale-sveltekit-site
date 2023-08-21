<script>
	import { fade } from 'svelte/transition';
</script>

<div class="back">
	<a href="/home">Home</a>
</div>
<div class="wrapper">
	<div class="container" in:fade={{ delay: 300, duration: 1000 }}>
		<div>
			<h1 class="title">Early Career:</h1>
		</div>
		<div>
			<p>My first interaction with the work force was actually quite unique.</p>
			<p>
				I lived in Watertown, New York when I was a teenager, and it was at this time that I started
				my career off not as an employee, but as a business owner. My brother Henry had run several
				businesses in the Watertown area, and we had formed a strong bond and decided to own and
				operate a small business together. So we started our buy, sell and trade store on Factory
				st, in Watertown Ny. It was definitely humble beginnings.
			</p>
			<p>
				We had no inventory and only a small amount of working capital to get started with, but we
				persevered. We put it in long hours, 7 day's a week getting our brick and mortar store set
				up and ready to go. I learned the value of hard work and determination to succeed at all
				cost.
			</p>
			<p>
				It paid off! Business was growing on a daily basis. I learned customer service, marketing
				and how to run the daily operations of a small business.
			</p>
			<p>
				Within 6 month's time we had grown so fast that we opened up our second location in
				Philadelphia, New York.
			</p>
			<p>
				This experience laid the foundation of the work ethic that I now hold. That through hard
				work, dedication, self improvement and learning, anything can be accomplished.
			</p>
		</div>
	</div>
	<div class="container" in:fade={{ delay: 500, duration: 1000 }}>
		<div>
			<h1 class="title">Middle Career:</h1>
		</div>
		<div>
			<p>
				I eventually moved to Boise, Idaho where I would join the workforce and dive head first into
				the manufacturing sector. It is over the next two decades where I would hone new skills, and
				learn about a new life changing philosophy, Kanban and Lean MFG. During these years I
				learned CNC manufacturing. I made it my goal to learn every CNC machine possible.
			</p>
			<p>I took right to it.</p>
			<p>These are the CNC Machines I learned during these years:</p>
			<p>1: CNC Punch Press</p>
			<p>2: CNC Press Brakes</p>
			<p>3: CNC Plasma Cutters</p>
			<p>4: CNC Lasers</p>
			<p>5: CNC Lathes</p>
			<p>6: CNC Mills, 3 and 4 axis machines</p>
			<p>I learned all about quality assurance, blueprint reading and manufacturing processes.</p>
			<p>
				I dove into using Auto Cad, and learning how to program all these machines as well using
				G-code language.
			</p>
			<p>Eventually I discovered the life changing philosophy of Kanban and Lean MFG.</p>
			<p>
				I became obsessed with how Kanban and Lean MFG working hand in hand, could drive up
				efficiency and reduce bottle necks.
			</p>
			<p>
				This eventually led me to become the go to guy for reducing cost, while increasing output
				with less labor cost. I began to design and implement Kanban systems for companies.
			</p>
			<p>
				During my time spent in the MFG community I was able to hold several management positions.
				Weekend supervisor, Night supervisor and plant supervisor at a very large manufacturing
				facility.
			</p>
			<p>
				I developed strong team leadership skills, which allowed me to bring the rest of the
				employees onboard with Kanban and Lean MFG. Change in culture is difficult, so strong
				leadership abilities was key to my success.
			</p>
		</div>
	</div>
	<div class="container" in:fade={{ delay: 700, duration: 1000 }}>
		<div>
			<h1 class="title">Present Day:</h1>
		</div>
		<div>
			<p>
				So we have arrived to present moment. Currently I reside in North Carolina, where I operate <a
					href="https://www.lighthousemaintenancellc.com/"
					target="_blank">Lighthouse Maintenance LLC</a
				> while I search for a role in tech. I started this company in 2016 in Boise, Idaho. I have since
				relocated it here to N.C
			</p>
			<p>
				Two years ago I made the decision that I wanted to become a developer. So I attended a full
				stack bootcamp with <a href="https://www.nucamp.co/" target="_blank">Nucamp.</a>
				I fell in love with coding right away. The learning, creativity and problem solving was everything
				I could ever want in a career.
			</p>
			<p>I am a constant learner, so this fit well with me.</p>
			<p>
				After graduating my bootcamp, I have continued the learning journey. I started taking extra
				courses through <a href="https://www.udemy.com/" target="_blank">Udemy.</a>
				Courses on Javscript, React, Node, ExpressJS, MongoDB, Svelte and SvelteKit, which is the tech
				I used to build this website.
			</p>
			<p>
				Being a developer is now where I call home. I think about coding all the time, it has become
				who I am.
			</p>
			<p>All that is left, is to turn this passion into a successful career.</p>
			<p>
				Currently I am working on my passion project the <a href="https://440club.com"> 440 Club</a>
				a website I created to showcase unsigned and smaller music artist. This site is a placeholder
				as I am working behind the scenes developing a new platform for music artist.
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
	a {
		color: #fff;
		text-decoration: none;
		cursor: pointer;
	}
	a:hover {
		color: #fff;
	}
	.back {
		margin: 1em 0 0 1em;
	}
	a {
		text-decoration: none;
		color: red;
	}
</style>
