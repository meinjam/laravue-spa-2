<template>
    <div>
        <h1>This is a vue component.</h1>
        <router-link :to="{ name: 'Home' }" class="btn btn-primary"
            >Add</router-link
        >
        <router-view />
    </div>
</template>
