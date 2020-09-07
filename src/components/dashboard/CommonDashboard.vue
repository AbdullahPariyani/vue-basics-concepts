<template>
	<div>
		<Header />
		<CarouselVue />
		<UserContent />
		<ChatDashboard />
		<Footer />
	</div>
</template>
<script>
import Header from '../common/Header.vue';
import CarouselVue from './Carousel.vue';
import UserContent from './UserContent.vue';
import Footer from '../common/Footer.vue';
import ChatDashboard from './ChatDashboard.vue';

export default {
	name: 'User Content',
	components: {
		Header,
		CarouselVue,
		UserContent,
		ChatDashboard,
		Footer,
	},
	props: {
		msg: String,
	},
};
</script>
<style scoped></style>
