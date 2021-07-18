<template>
  <nav class="navbar navbar-expand-lg navbar-light">
    <div class="container">
			<router-link to="/" class="navbar-brand">Wesley Burch</router-link>
			<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
			<span class="navbar-toggler-icon"></span>
			</button>
			<div class="collapse navbar-collapse" id="navbarNav">
				<ul class="navbar-nav ms-auto">
					<li class="nav-item">
						<router-link to="/portfolio" class="nav-link" aria-current="page" >Portfolio</router-link>
					</li>
					<li class="nav-item">
						<router-link to="/about" class="nav-link" aria-current="page" >About</router-link>
					</li>
					<li class="nav-item">
						<router-link to="/contact" class="nav-link" aria-current="page" >Contact</router-link>
					</li>
					<li class="nav-item">
						<router-link to="/blog" class="nav-link" aria-current="page" >Blog</router-link>
					</li>
				</ul>
			</div>
		</div>
	</nav>
</template>

<script>
export default {
	name: 'Navigation',
	props: {
	}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
