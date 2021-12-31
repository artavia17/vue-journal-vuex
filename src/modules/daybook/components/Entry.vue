<template>
    <div
        class="entry-container mb-3 pointer p-2"
        @click="$router.push({ name: 'entry', params: { id: 10 } })"
    >
    <!-- Titulo de esta entrada -->
        <div 
            class="entry-title d-flex"
        >
            <span class="text-success fs-4 fw-bold">15</span>
            <span class="mx-1 fs-5" >Julio</span>
            <span class="mx-2 fw-light" >2021, jueves</span>
        </div>

        <div class="entry-description">

           <p> Sint deserunt elit ex exercitation sint amet enim Lorem laboris enim excepteur Lorem minim. Enim nostrud nisi aliquip laboris commodo proident fugiat cillum incididunt laboris duis occaecat. Lorem exercitation consectetur sunt excepteur dolor. Do sit Lorem nostrud velit dolore. Culpa ut in in ullamco ad aliquip nisi voluptate et ullamco. </p>

        </div>

    </div>
</template>
<script>
export default {
    
}
</script>

<style lang="scss" scoped>

    .entry-container{
        border-bottom: 1px solid #3c3e50;
        transition: 0.2s all ease-in;

        &:hover {
            
            background-color: lighten($color: green, $amount: 45);
            transition: 0.2s all ease-in;

        }

    }

    .entry-description{
        font-size: 12px;
    }

</style>