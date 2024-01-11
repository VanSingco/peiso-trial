<template>
    <div>
        <DashboardLayout>
            <div class="dashboard">
                <HeaderMenu />

                <div class="dashboard__stats">
                    <el-button-group>
                        <el-button class="btn-primary">
                            Today
                            <el-icon class="el-icon--right"><ArrowDown /></el-icon>
                        </el-button>
                        <el-button class="btn-default">
                            Weekly
                        </el-button>
                    </el-button-group>

                    <StatsCard />
                </div>



            </div>
        </DashboardLayout>
        
    </div>
</template>

<script>
    import { ArrowDown } from '@element-plus/icons-vue'
    import DashboardLayout from '@/components/layouts/DashboardLayout.vue'
    import HeaderMenu from '@/components/dashboard/HeaderMenu.vue';
    import StatsCard from '@/components/dashboard/StatsCard.vue';
    export default {
        components: { DashboardLayout, ArrowDown, HeaderMenu, StatsCard},
    }
</script>