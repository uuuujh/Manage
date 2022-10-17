<template>
    <div>
        <el-row :gutter="10">
            <el-col :span="12">
                <Search></Search>
            </el-col>
            <el-col :span="12">
                <category></category>
            </el-col>
        </el-row>

    </div>
</template>

<script>
import Category from './Category/index.vue'
import Search from './Search/index.vue'
export default {
    name: "Observe",
    components: {
        Category,
        Search
    }
}
</script>

<style scoped>

</style>