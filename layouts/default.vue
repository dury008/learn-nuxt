<template>
    <div>
        <h2>{{$route.name}}페이지</h2>
        <NuxtLink to="/">인덱스 페이지</NuxtLink>
        <NuxtLink to="/main">메인 페이지</NuxtLink>
        <NuxtLink to="/product">상품 페이지</NuxtLink>
        
        <Nuxt/>
    </div>
</template>

<script>
    export default {}
</script>

<style></style>