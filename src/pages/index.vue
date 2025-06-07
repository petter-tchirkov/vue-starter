<script setup lang="ts">
import { RouterLink } from 'vue-router';
</script>

<template>
	<h1>This is home</h1>
	<RouterLink to="/about">to about</RouterLink>
	<RouterLink to="/users/abc">to user</RouterLink>
</template>
