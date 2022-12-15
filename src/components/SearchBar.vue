<script setup>
import platforms from "@/assets/platforms.json";

let toPrint = tagsToFilter

// export default {
//     setup() {
//         let tagsToFilter = ref("")
//         //let listOfPlatforms = platforms
//         const filteredList = computed(() => {
//             let filteredTags = tagsToFilter.value
//             if (!filter.length) return platforms
//             return platforms.filter((item) => item.tags.includes(filteredTags))
//         })
//         return {
//             tagsToFilter,
//             filteredList,
//         }
//     }
// }

</script>

<template>
    <div class="search-bar">
            <input class="search-box" v-model="tagsToFilter" placeholder="Filter by tag..."/>
    </div>
    <ul>
        <li v-for="item in platforms" class="blue">
            {{ item.title }}, {{ toPrint }}
        </li>
    </ul>
</template>