<template>
	<svg :style="svgStyle" viewBox="0 0 24 24">
		<path
			fill="currentColor"
			d="M3 11q0 1.8 1.15 3.175T7.075 15.9l-.775-.775q-.275-.275-.275-.687t.275-.713q.3-.3.713-.3t.712.3L10.3 16.3q.3.3.3.7t-.3.7l-2.6 2.6q-.275.275-.7.275t-.725-.3Q6 20 6 19.6t.275-.7l.9-.95q-2.65-.3-4.412-2.287T1 11q0-2.925 2.038-4.962T8 4h2q.425 0 .713.288T11 5t-.288.713T10 6H8Q5.925 6 4.463 7.463T3 11m11 9q-.425 0-.712-.288T13 19v-5q0-.425.288-.712T14 13h7q.425 0 .713.288T22 14v5q0 .425-.288.713T21 20zm0-9q-.425 0-.712-.288T13 10V5q0-.425.288-.712T14 4h7q.425 0 .713.288T22 5v5q0 .425-.288.713T21 11zm1-2h5V6h-5z"
		/>
	</svg>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import icon from "@/mixins/icon";

export default defineComponent({
	name: "Hems",
	mixins: [icon],
});
</script>
