<script>
	export let name;
</script>

<main>
	<h1>Let's start a project</h1>
	<p>Interested in working with us? Please fill out the form below and we'll be in touch.</p>

	<br/>
	<div>
		<h2>The Basics</h2>
		<input placeholder="Name"/>
		<input placeholder="Company"/>
		<input placeholder="Email"/>
		<input placeholder="Website or LinkedIn (Optional)"/>
	</div>

	<div>
		<h2>What are your goals?</h2>
		<p>You can select more than one...</p>
		<ul>
			<li>Increase my audience</li>
			<li>Improve the efficiency of my digital ecosystem</li>
			<li>Improve my engagement</li>
			<li>Gather insights about my customers</li>
			<li>Create a new digital project</li>
			<li>Other</li>
		</ul>
	</div>

	<div>
		<h2>What is your budget?</h2>
		<p>A gu-estimate is fine...</p>
		<input type="range" min="2000" max="750,000"/>
	</div>

	<div>
		<h2>When would you like to get started</h2>
		<select>
			<option>As soon as possible</option>
			<option>During the next quarter</option>
			<option>This year</option>
			<option>Let's discuss it</option>
		</select>
	</div>

	<div>
		<h2>How did you hear about us</h2>
		<p>You can select more than one...</p>
		<ul>
			<li>Google search</li>
			<li>Social media</li>
			<li>LinkedIn</li>
			<li>Word of mouth</li>
			<li>Podcast</li>
			<li>New work</li>
			<li>Referral</li>
			<li>Client Work (please specify)</li>
			<li>Other (please specify)</li>
		</ul>
	</div>

	<button>submit</button>
</main>

<style>
</style>