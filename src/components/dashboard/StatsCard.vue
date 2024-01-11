<template>
    <div class="dashboard__stats--cards">
        <el-row :gutter="10">
            <el-col :xs="24" :sm="24" :md="12" class="mb-20">

                <Card color="#fff">
                    <template v-slot:header>
                        <div class="custom-text-2">
                            <span>Guidance</span>
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none">
                                <path fill-rule="evenodd" clip-rule="evenodd" d="M2 12C2 6.47715 6.47715 2 12 2C17.5202 2.00633 21.9937 6.47978 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12ZM3.66656 12.0002C3.66656 16.6026 7.39753 20.3335 11.9999 20.3335C16.6001 20.3284 20.3281 16.6004 20.3332 12.0002C20.3332 7.39783 16.6023 3.66687 11.9999 3.66687C7.39753 3.66687 3.66656 7.39783 3.66656 12.0002ZM16.21 12.8331H6.97139C6.64965 12.844 6.36285 13.0464 6.23501 13.3528C6.10716 13.6591 6.16121 14.0144 6.37379 14.2651L9.42056 17.574C9.61462 17.7889 9.90499 17.8792 10.1811 17.8105C10.4571 17.7419 10.6764 17.5248 10.7553 17.2421C10.8343 16.9593 10.7608 16.6544 10.5628 16.4434L8.74631 14.4713H16.21C16.6462 14.4713 16.9999 14.1046 16.9999 13.6522C16.9999 13.1998 16.6462 12.8331 16.21 12.8331ZM16.195 11.1665H6.95619V11.1669C6.52009 11.1669 6.16656 10.7999 6.16656 10.3472C6.16656 9.89452 6.52009 9.52755 6.95619 9.52755H14.4199L12.6035 7.55258C12.4087 7.34078 12.3376 7.03718 12.4169 6.75615C12.4962 6.47512 12.7139 6.25935 12.988 6.19012C13.2621 6.12089 13.551 6.20872 13.7458 6.42052L16.7926 9.73305C17.0052 9.98397 17.0593 10.3397 16.9315 10.6464C16.8036 10.9531 16.5168 11.1556 16.195 11.1665Z" fill="#EA3796"/>
                            </svg>
                        </div>
                    </template>

                    <template v-slot:body>
                        <div class="custom-text-1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none">
                                <path fill-rule="evenodd" clip-rule="evenodd" d="M4.92893 4.92893C6.73783 3.12005 9.23879 2 12 2C14.7612 2 17.2622 3.12005 19.0711 4.92893L18.5777 5.42226L19.0711 4.92893C20.8799 6.73783 22 9.23879 22 12C22 14.7612 20.8799 17.2622 19.0711 19.0711C17.2622 20.8799 14.7612 22 12 22C9.23879 22 6.73783 20.8799 4.92893 19.0711L5.42226 18.5777L4.92893 19.0711C3.12005 17.2622 2 14.7612 2 12C2 9.23879 3.12005 6.73783 4.92893 4.92893L4.92893 4.92893ZM12 3.39535C9.62372 3.39535 7.47351 4.35769 5.91559 5.91559C4.35769 7.47352 3.39535 9.62372 3.39535 12C3.39535 14.3763 4.35769 16.5265 5.91559 18.0844C7.47352 19.6423 9.62372 20.6047 12 20.6047C14.3763 20.6047 16.5265 19.6423 18.0844 18.0844C19.6423 16.5265 20.6047 14.3763 20.6047 12C20.6047 9.62372 19.6423 7.47352 18.0844 5.91559C16.5265 4.35769 14.3763 3.39535 12 3.39535Z" fill="#34C759"/>
                                <path fill-rule="evenodd" clip-rule="evenodd" d="M17.2803 8.21967C17.5732 8.51256 17.5732 8.98744 17.2803 9.28033L11.2803 15.2803C10.9874 15.5732 10.5126 15.5732 10.2197 15.2803L7.21967 12.2803C6.92678 11.9874 6.92678 11.5126 7.21967 11.2197C7.51256 10.9268 7.98744 10.9268 8.28033 11.2197L10.75 13.6893L16.2197 8.21967C16.5126 7.92678 16.9874 7.92678 17.2803 8.21967Z" fill="#34C759"/>
                            </svg>
                            <h1>
                                Well Done,Your revenue reaches the target
                            </h1>
                        </div>
                    </template>
                </Card>

            </el-col>
            <el-col :xs="24" :sm="24" :md="12" class="mb-20">
                <Card color="#EA3796" :iconType="'edit'">
                    
                    <template v-slot:body>
                        <h1 class="custom-text-3">
                            END OF THE DAY <br> REPORT
                        </h1>
                    </template>
                </Card>

            </el-col>
            <el-col :xs="24" :sm="24" :md="12" class="mb-20">
                <Card color="#FFF" :iconType="'edit'">
                    <template v-slot:header>
                        <span>Revenue Target</span>
                    </template>
                    <template v-slot:body>
                        <h1 class="custom-text-4">
                            $10,000
                        </h1>
                    </template>
                </Card>
            </el-col>
            <el-col :xs="24" :sm="24" :md="12" class="mb-20">
                <Card color="#2FCBFF" :iconType="'edit'">
                    <template v-slot:header>
                        <span>Actual Revenue</span>
                    </template>
                    <template v-slot:body>
                        <h1 class="custom-text-4">
                            $8,000
                        </h1>
                    </template>
                </Card>
            </el-col>
            <el-col :xs="24" :sm="24" :md="12" class="mb-20">
                <Card color="#FFF" :iconType="'filter'">
                    <template v-slot:header>
                        <span>Target Roster</span>
                    </template>
                    <template v-slot:body>
                        <h1 class="custom-text-4">
                            $2,000
                        </h1>
                    </template>
                </Card>
            </el-col>
            <el-col :xs="24" :sm="24" :md="12" class="mb-20">
                <Card color="#2FCBFF" :iconType="'filter'">
                    <template v-slot:header>
                        <span>Actual Roster</span>
                    </template>
                    <template v-slot:body>
                        <h1 class="custom-text-4">
                            $1,900
                        </h1>
                    </template>
                </Card>
            </el-col>

            <el-col :span="24" class="mb-20">
                <Card color="#FFF" :cardTable="true">
                    <template v-slot:header>
                        <span>Actual Weekly Operation</span>
                    </template>
                    <template v-slot:body>
                        <el-table class="table" :data="tableData" border>
                            <el-table-column prop="name" label="" width="180">
                                <template #default="scope">
                                    <template v-if="scope.row.name == 'Labour +/-'">
                                        <div class="custom-text-5">
                                            <span>{{ scope.row.name }}</span>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="18" height="19" viewBox="0 0 18 19" fill="none">
                                                <path fill-rule="evenodd" clip-rule="evenodd" d="M0 9.63037C0 4.65981 4.02944 0.630371 9 0.630371C13.9682 0.636072 17.9943 4.66217 18 9.63037C18 14.6009 13.9706 18.6304 9 18.6304C4.02944 18.6304 0 14.6009 0 9.63037ZM1.5 9.63037C1.5 13.7725 4.85786 17.1304 9 17.1304C13.1402 17.1257 16.4954 13.7706 16.5 9.63037C16.5 5.48824 13.1421 2.13037 9 2.13037C4.85786 2.13037 1.5 5.48824 1.5 9.63037ZM12.7891 10.3804H4.47435C4.18478 10.3902 3.92666 10.5723 3.8116 10.848C3.69654 11.1237 3.74518 11.4435 3.9365 11.6691L6.6786 14.6472C6.85325 14.8406 7.11459 14.9218 7.36305 14.86C7.61151 14.7982 7.80886 14.6029 7.87991 14.3484C7.95096 14.0939 7.88478 13.8195 7.70658 13.6296L6.07177 11.8547H12.7891C13.1817 11.8547 13.5 11.5247 13.5 11.1175C13.5 10.7104 13.1817 10.3804 12.7891 10.3804ZM12.7756 8.88006H4.46066V8.88037C4.06817 8.88037 3.75 8.55009 3.75 8.14268C3.75 7.73526 4.06817 7.40498 4.46066 7.40498H11.178L9.54328 5.62751C9.36795 5.43689 9.30391 5.16365 9.37527 4.91073C9.44664 4.6578 9.64258 4.46361 9.88928 4.4013C10.136 4.33899 10.396 4.41804 10.5713 4.60866L13.3135 7.58993C13.5048 7.81576 13.5535 8.13591 13.4384 8.41193C13.3233 8.68794 13.0652 8.87027 12.7756 8.88006Z" fill="#D13A90"/>
                                            </svg> 
                                        </div>
                                    </template>
                                    <template v-else>
                                        {{ scope.row.name }} 
                                    </template>
                                    
                                </template>
                            </el-table-column>
                            <el-table-column prop="mon" label="Mon">
                                <template #default="scope">
                                    <span :class="`${getColor(scope.row.mon)}`">{{scope.row.mon != '0' ? formatNumber (scope.row.mon) : '-'}}</span>
                                </template>
                            </el-table-column>
                            <el-table-column prop="tue" label="Tue">
                                <template #default="scope">
                                    <span :class="`${getColor(scope.row.tue)}`">{{scope.row.tue != '0' ? scope.row.tue : '-'}}</span>
                                </template>
                            </el-table-column>
                            <el-table-column prop="wed" label="Wed">
                                <template #default="scope">
                                    <span :class="`${getColor(scope.row.wed)}`">{{scope.row.wed != '0' ? scope.row.wed : '-'}}</span>
                                </template>
                            </el-table-column>
                            <el-table-column prop="thu" label="Thu">
                                <template #default="scope">
                                    <span :class="`${getColor(scope.row.thu)}`">{{scope.row.thu != '0' ? scope.row.thu : '-'}}</span>
                                </template>
                            </el-table-column>
                            <el-table-column prop="fri" label="Fri">
                                <template #default="scope">
                                    <span :class="`${getColor(scope.row.fri)}`">{{scope.row.fri != '0' ? scope.row.fri : '-'}}</span>
                                </template>
                            </el-table-column>
                            <el-table-column prop="sat" label="Sat">
                                <template #default="scope">
                                    <span :class="`${getColor(scope.row.sat)}`">{{scope.row.sat != '0' ? scope.row.sat : '-'}}</span>
                                </template>
                            </el-table-column>
                            <el-table-column prop="sun" label="Sun">
                                <template #default="scope">
                                    <span :class="`${getColor(scope.row.sun)}`">{{scope.row.sun != '0' ? scope.row.sun : '-'}}</span>
                                </template>
                            </el-table-column>
                            <el-table-column prop="total" label="Total">
                                <template #default="scope">
                                    <span :class="`${getColor(scope.row.total)}`">{{scope.row.total != '0' ? scope.row.total : '-'}}</span>
                                </template>
                            </el-table-column>

                        </el-table>
                    </template>
                </Card>
            </el-col>

            <el-col :span="24" class="mb-20">
                <Card color="#FFF" :cardTable="true">
                    <template v-slot:header>
                        <div class="custom-table-header">
                            <div class="custom-text-2">
                                <span>Weekly Labour</span>
                                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none">
                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M2 12C2 6.47715 6.47715 2 12 2C17.5202 2.00633 21.9937 6.47978 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12ZM3.66656 12.0002C3.66656 16.6026 7.39753 20.3335 11.9999 20.3335C16.6001 20.3284 20.3281 16.6004 20.3332 12.0002C20.3332 7.39783 16.6023 3.66687 11.9999 3.66687C7.39753 3.66687 3.66656 7.39783 3.66656 12.0002ZM16.21 12.8331H6.97139C6.64965 12.844 6.36285 13.0464 6.23501 13.3528C6.10716 13.6591 6.16121 14.0144 6.37379 14.2651L9.42056 17.574C9.61462 17.7889 9.90499 17.8792 10.1811 17.8105C10.4571 17.7419 10.6764 17.5248 10.7553 17.2421C10.8343 16.9593 10.7608 16.6544 10.5628 16.4434L8.74631 14.4713H16.21C16.6462 14.4713 16.9999 14.1046 16.9999 13.6522C16.9999 13.1998 16.6462 12.8331 16.21 12.8331ZM16.195 11.1665H6.95619V11.1669C6.52009 11.1669 6.16656 10.7999 6.16656 10.3472C6.16656 9.89452 6.52009 9.52755 6.95619 9.52755H14.4199L12.6035 7.55258C12.4087 7.34078 12.3376 7.03718 12.4169 6.75615C12.4962 6.47512 12.7139 6.25935 12.988 6.19012C13.2621 6.12089 13.551 6.20872 13.7458 6.42052L16.7926 9.73305C17.0052 9.98397 17.0593 10.3397 16.9315 10.6464C16.8036 10.9531 16.5168 11.1556 16.195 11.1665Z" fill="#EA3796"/>
                                </svg>
                            </div>
                            <router-link to="#" class="custom-text-6">
                                <span>Details</span>
                                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none">
                                    <path d="M14.1667 6C13.9534 6 13.74 6.08285 13.5775 6.24577L13.5059 6.31738C13.18 6.64322 13.18 7.17077 13.5059 7.49577L16.7253 10.7152H5.83333C5.37333 10.7152 5 11.0885 5 11.5485C5 12.0085 5.37333 12.3818 5.83333 12.3818H16.7253L13.5059 15.6012C13.18 15.9271 13.18 16.4546 13.5059 16.7796L13.5775 16.8512C13.9033 17.1771 14.4309 17.1771 14.7559 16.8512L19.4694 12.1377C19.7952 11.8119 19.7952 11.2843 19.4694 10.9593L14.7559 6.24577C14.5929 6.08285 14.3799 6 14.1667 6Z" fill="#EA3796"/>
                                </svg>
                            </router-link>
                        </div>
                    </template>
                    <template v-slot:body>
                        <el-table class="table" :data="tableData2" border>
                            <el-table-column prop="name" label="" width="180">
                                <template #default="scope">
                                    {{ scope.row.name }} 
                                </template>
                            </el-table-column>
                            <el-table-column prop="mon" label="Mon">
                                <template #default="scope">
                                    <span>{{scope.row.mon}}</span>
                                </template>
                            </el-table-column>
                            <el-table-column prop="tue" label="Tue">
                                <template #default="scope">
                                    <span>{{scope.row.tue}}</span>
                                </template>
                            </el-table-column>
                            <el-table-column prop="wed" label="Wed">
                                <template #default="scope">
                                    <span>{{scope.row.wed}}</span>
                                </template>
                            </el-table-column>
                            <el-table-column prop="thu" label="Thu">
                                <template #default="scope">
                                    <span>{{scope.row.thu}}</span>
                                </template>
                            </el-table-column>
                            <el-table-column prop="fri" label="Fri">
                                <template #default="scope">
                                    <span>{{scope.row.fri}}</span>
                                </template>
                            </el-table-column>
                            <el-table-column prop="sat" label="Sat">
                                <template #default="scope">
                                    <span>{{scope.row.sat}}</span>
                                </template>
                            </el-table-column>
                            <el-table-column prop="sun" label="Sun">
                                <template #default="scope">
                                    <span>{{scope.row.sun}}</span>
                                </template>
                            </el-table-column>
                            <el-table-column prop="total" label="Total">
                                <template #default="scope">
                                    <span>{{scope.row.total}}</span>
                                </template>
                            </el-table-column>

                        </el-table>
                    </template>
                </Card>
            </el-col>
        </el-row>
    </div>
</template>

<script>
    import Card from '@/components/Card.vue';
    export default {
        components: { Card },
        data() {
            return {
                tableData: [
                    {
                        name: 'Labour +/-',
                        mon:  '+20',
                        tue:  '-20',
                        wed:  '-10',
                        thu:  '-5',
                        fri:  '0',
                        sat:  '0',
                        sun:  '0',
                        total: '-15'
                    },
                    {
                        name: 'Rev +/-',
                        mon:  '+200',
                        tue:  '-1200',
                        wed:  '-2000',
                        thu:  '-400',
                        fri:  '0',
                        sat:  '0',
                        sun:  '0',
                        total:  '-1000',
                    }
                ],

                tableData2: [
                    {
                        name: 'Actuals Labour',
                        mon:  '$1,200',
                        tue:  '$1,200',
                        wed:  '$1,200',
                        thu:  '$900',
                        fri:  '-',
                        sat:  '-',
                        sun:  '-',
                        total: '$4,500'
                    },
                    {
                        name: 'Rostered Labour',
                        mon:  '$1,200',
                        tue:  '$1,200',
                        wed:  '$1,200',
                        thu:  '$1,200',
                        fri:  '$1,200',
                        sat:  '$1,200',
                        sun:  '$1,200',
                        total:  '$8,400',
                    }
                ],
            }
        },

        methods: {
            getColor(str) {
                // Parse the string into a number
                const number = parseInt(str);

                if (str == '0') {
                    return 'text-white'
                }

                // Check if the number is NaN (Not a Number)
                if (isNaN(number)) {
                    console.log("Invalid number");
                    return false; // or handle the error accordingly
                }

                // Check if the number is negative
                return number < 0 ? 'text-red' : 'text-green';
            },

            formatNumber (number) {

                return number;
            }
        },
    }
</script>