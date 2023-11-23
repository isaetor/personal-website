<script setup>
import Header from "./components/Header.vue"
import Footer from "./components/Footer.vue"
</script>

<template>
    <Header />
    <section class="relative container px-4 py-28 mx-auto flex items-center justify-between gap-40">
        <div class="w-7/12 space-y-6">
            <div class="absolute top-32 -right-12 flex flex-wrap w-72 gap-3 -z-10">
                <div v-for="index in 100" :key="index" class="w-4 h-4 bg-white/30 rounded-full"></div>
            </div>
            <h1 class="text-5xl leading-[5rem] font-black text-neutral-600">
                <span class="block">درود فراوان</span>
                <span class="block">من <span class="text-blue-500">سعید ترکمان</span> هستم</span>
                <span class="block">برنامه نویس تحت وب</span>
            </h1>
            <p class="text-2xl leading-10">لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ، و با استفاده از طراحان گرافیک است، چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است</p>
            <div class="flex items-center gap-6">
                <button class="py-2 px-6 rounded-md bg-blue-500 text-white hover:bg-blue-600">خدمات</button>
                <button class="border py-2 px-3 rounded-md border-blue-500 text-blue-500 hover:border-blue-600 hover:text-blue-600">دانلود رزومه</button>
            </div>
        </div>
        <div class="w-5/12 ">
            <div class="absolute top-[136px] -left-[60px] p-2 bg-white rounded-3xl">
                <div class="bg-[url('/lang.png')] w-24 h-24 bg-[length:300px] bg-[-3px_-100px]"></div>
            </div>
            <div class="absolute top-[260px] -left-[60px] p-2 bg-white rounded-3xl">
                <div class="bg-[url('/lang.png')] w-24 h-24 bg-[length:300px] bg-[-187px_-100px]"></div>
            </div>
            <div class="absolute top-[530px] -left-[60px] p-2 bg-white rounded-3xl">
                <div class="bg-[url('/lang.png')] w-24 h-24 bg-[length:280px] bg-[-99px_0px]"></div>
            </div>
            <div class="absolute top-[470px] left-[480px] p-2 bg-white rounded-3xl">
                <div class="bg-[url('/lang.png')] w-24 h-24 bg-[length:350px] bg-[-10px_-242px]"></div>
            </div>
            <div class="absolute top-[594px] left-[480px] p-2 bg-white rounded-3xl">
                <div class="bg-[url('/lang.png')] w-24 h-24 bg-[length:300px] bg-[-206px_-5px]"></div>
            </div>
            <div class="absolute top-[594px] left-[604px] p-2 bg-white rounded-3xl">
                <div class="bg-[url('/lang.png')] w-24 h-24 bg-[length:260px] bg-[-83px_-170px]"></div>
            </div>
            <div class="absolute top-[260px] left-[480px] p-2 bg-white rounded-3xl">
                <div class="bg-[url('/lang.png')] w-24 h-24 bg-[length:300px] bg-[-95px_-100px]"></div>
            </div>
            <img class="w-full h-auto" src="./assets/images/user.png" alt="Saeed Torkaman">
        </div>
    </section>
    <section class="container px-4 py-12 mx-auto">
        
        <div class="relative flex flex-col justify-center mb-12">
            <div class="absolute -top-5 -right-16 flex flex-wrap w-11 gap-3 -z-10">
                <div v-for="index in 12" :key="index" class="w-4 h-4 bg-white/30 rounded-full"></div>
            </div>
            <h2 class="text-xl font-bold text-blue-500 mb-3">خدمات</h2>
            <p class="text-3xl font-black text-neutral-600 mb-4">طراحی و اجرای حرفه ای خدمات</p>
            <p class="text-xl">خدماتی که ارائه میدهم</p>
        </div>
        <div class="relative grid grid-cols-3 gap-3">
            <div class="relative grid-cols-1 cursor-pointer before:w-full  before:h-full before:absolute before:border-2 before:border-blue-300 before:border-dashed before:rounded-2xl before:z-0">
                <div class="relative bg-white rounded-2xl z-10 p-2 flex items-center gap-3 duration-500 hover:-translate-y-2 hover:translate-x-2">
                    <i class="iconly-Category text-9xl text-blue-300"></i>
                    <div  class="flex flex-col justify-center gap-2 pl-5">
                        <h3 class="font-bold text-lg text-neutral-800">طراحی سلایت</h3>
                        <p>طراحی انواع سایت های فروشگاهی ، خبری ، وبلاگی و ...</p>
                    </div>
                </div>
            </div>
            <div class="relative grid-cols-1 cursor-pointer before:w-full  before:h-full before:absolute before:border-2 before:border-blue-300 before:border-dashed before:rounded-2xl before:z-0">
                <div class="relative bg-white rounded-2xl z-10 p-2 flex items-center gap-3 duration-500 hover:-translate-y-2 hover:translate-x-2">
                    <i class="iconly-Discount text-9xl text-blue-300"></i>
                    <div  class="flex flex-col justify-center gap-2 pl-5">
                        <h3 class="font-bold text-lg text-neutral-800">طراحی اپلیکیشن</h3>
                        <p>طراحی و اجرای انواع اپلیکشن های SPA و تحت وب</p>
                    </div>
                </div>
            </div>
            <div class="relative grid-cols-1 cursor-pointer before:w-full  before:h-full before:absolute before:border-2 before:border-blue-300 before:border-dashed before:rounded-2xl before:z-0">
                <div class="relative bg-white rounded-2xl z-10 p-2 flex items-center gap-3 duration-500 hover:-translate-y-2 hover:translate-x-2">
                    <i class="iconly-Graph text-9xl text-blue-300"></i>
                    <div  class="flex flex-col justify-center gap-2 pl-5">
                        <h3 class="font-bold text-lg text-neutral-800">خدمات وردپرس</h3>
                        <p>انجام خدماتی همچوت طراحی قالب و افزونه اختصاصی وردپرس</p>
                    </div>
                </div>
            </div>
        </div>
        
    </section>
    <Footer />
</template>
