<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Testando alguns recursos de desenvolvimento</div>

                    <div class="card-body">
                        Exemplaço da massa.
                            <input type="text" v-model="test">
                            {{test}}
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        data: () => {
           return{
            test: ''
        }
            },
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
