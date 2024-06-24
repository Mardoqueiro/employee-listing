<template>
    <div class="card" >
        <slot name="cardheader"></slot>
        <div class="card-body">
            <slot name="cardbody"></slot>
        </div>
    </div>
</template>
    
<script>
export default {
  name: 'CardComp',
};
</script>

<style scoped>
.card {
  width: 18rem;
}

</style>
    