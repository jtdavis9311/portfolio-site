<template>
	<div id="home">

		<div :class="['left', hover]">
			<h1>Jordan Davis</h1>
			<p>Front End Engineer, <a class="milkshake" href="https://milkshake.studio/">Milkshake Studio</a></p>

			<div class="links">
				<a href="https://github.com/jtdavis9311"><Github></Github></a>
				<a href="https://www.linkedin.com/in/jordantd/"><Linkedin></Linkedin></a>
			</div>
		</div>
		
		<div class="right">
			<a href="https://www.myclean.com/" target="_blank">
				<p>MyClean</p>
				<!-- <p>MyClean</p> -->
				<!-- <p>MyClean</p> -->
				<!-- <p>MyClean</p> -->
				<!-- <p>MyClean</p> -->
				<!-- <p>MyClean</p> -->
			</a>
			<a href="https://www.olo.com/" target="_blank">
				<p>Olo</p>
				<!-- <p>Olo</p> -->
				<!-- <p>Olo</p> -->
				<!-- <p>Olo</p> -->
				<!-- <p>Olo</p> -->
				<!-- <p>Olo</p> -->
				<!-- <p>Olo</p> -->
			</a>
			<a href="https://timeequities.com/" target="_blank">
				<p>Time Equities Inc.</p>
				<!-- <p>Time Equities Inc.</p> -->
				<!-- <p>Time Equities Inc.</p> -->
				<!-- <p>Time Equities Inc.</p> -->
			</a>
			<a href="https://crunchtime.com/" target="_blank">
				<p>CrunchTime!</p>
				<!-- <p>CrunchTime!</p> -->
				<!-- <p>CrunchTime!</p> -->
				<!-- <p>CrunchTime!</p> -->
			</a>
			<a href="https://proplete.com/" target="_blank">
				<p>Proplete</p>
				<!-- <p>Proplete</p> -->
				<!-- <p>Proplete</p> -->
				<!-- <p>Proplete</p> -->
				<!-- <p>Proplete</p> -->
				<!-- <p>Proplete</p> -->
			</a>
			<a href="https://projectentrepreneur.org/" target="_blank">
				<p>Project Entrepreneur</p>
				<!-- <p>Project Entrepreneur</p> -->
				<!-- <p>Project Entrepreneur</p> -->
				<!-- <p>Project Entrepreneur</p> -->
			</a>
			<a href="https://yellowgoatdesign.com/" target="_blank">
				<p>Yellow Goat Design</p>
				<!-- <p>Yellow Goat Design</p> -->
				<!-- <p>Yellow Goat Design</p> -->
				<!-- <p>Yellow Goat Design</p> -->
			</a>
			<a href="https://chestertravels.com/" target="_blank">
				<p>Chester</p>
				<!-- <p>Chester</p> -->
				<!-- <p>Chester</p> -->
				<!-- <p>Chester</p> -->
				<!-- <p>Chester</p> -->
				<!-- <p>Chester</p> -->
			</a>
			<a href="https://iendorsebooker.com/" target="_blank">
				<p>I Endorse Booker</p>
				<!-- <p>I Endorse Booker</p> -->
				<!-- <p>I Endorse Booker</p> -->
				<!-- <p>I Endorse Booker</p> -->
			</a>
		</div>
	</div>
</template>

<script>
import Github from './github';
import Linkedin from './linkedin';

export default {
	name: 'Home',
	components: {
		Github,
		Linkedin,
	},
}

</script>