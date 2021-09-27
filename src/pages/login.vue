<template>
    <div class="row">
        <div class="col-md-7 col-sm-7 col-lg-7">
            <q-img src="~/assets/bg-01.jpg" style="height: 700px;"></q-img>
        </div>
        <div class="col-md-5 col-sm-5 col-lg-5">
            <div>
                <div class="text-h6 text-center text-blod q-pt-xl q-mt-xl">Login to continue</div>
            </div>
            <div class="q-pa-sm">
                <q-input v-model="username" label="Username" ></q-input>
                <q-input v-model="password" label="Password" ></q-input>
            </div>
            <div class="">
                <q-checkbox v-model="check" label="Remember me"></q-checkbox>
                <a href="#" class="float-right" style="text-decoration: none;">Forgot Password</a>
                <q-btn label="Login" style="width: 100%" class="bg-primary text-white"></q-btn>
            </div>
        </div>
    </div>
</template>

<script>

export default { 
    name: "Login",
    data(){
        return {
            check: false,
            username: '',
            password: ''
        }
    }
}
</script>
