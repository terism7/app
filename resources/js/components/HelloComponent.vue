<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-12">
                <div class="card card-default">
                    <div class="card-header">{{pageName}}</div>
                    <div class="card-body">
                        Hello World
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        data: function() {
            return {
                pageName: 'CRUD VueJS Have Fun!'
            }
        },
        mounted() {
            console.log('Hello World Mounted.')
        }
    }
</script>
