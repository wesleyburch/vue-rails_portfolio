<template>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <h2>Projects I've Worked On</h2>
                <PortfolioItem />
            </div>
        </div>
    </div>
</template>

<script>
import PortfolioItem from '@/components/PortfolioItem.vue'

export default {
	name: 'Portfolio',
	components: {
		PortfolioItem
	}
}
</script>

// <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
