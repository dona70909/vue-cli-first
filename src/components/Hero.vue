<template>
    <div class="hello">
        <img :src="link" alt="Labrador">
    </div>
</template>

<script>
export default {
    name: "HelloWorld",
    props: {
        link: String
    }
}
</script>

