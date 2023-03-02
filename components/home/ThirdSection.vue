<template>
    <div class="bg-black relative">
        <Container class="h-[520px] w-100 ">
            <div class="absolute top-0 bottom-0 right-0 left-0 flex justify-center items-center flex-col z-10">
                <p class="text-center uppercase text-white cffont text-[55px] -mb-6">Déjà plus de</p>
                <p class="text-center uppercase text-[#B188EA] text-[55px] cffont">250 collaborations</p>
            </div>
            <div id="colab1" class="absolute top-0 left-0 bg-white w-[240px] h-[190px] bg-cover bg-no-repeat"></div>
            <div id="colab2" class="absolute bottom-0 left-[100px] bg-white w-[240px] h-[290px] bg-cover bg-no-repeat"></div>
            <div id="colab3" class="absolute top-[35px] left-[550px] bg-white w-[175px] h-[212px] bg-cover bg-no-repeat"></div>
            <div id="colab4" class="absolute bottom-0 right-[550px] bg-white w-[255px] h-[118px] bg-cover bg-no-repeat"></div>
            <div id="colab5" class="absolute top-0 right-[100px] bg-white w-[175px] h-[212px] bg-cover bg-no-repeat"></div>
            <div id="colab5" class="absolute bottom-0 right-[30px] bg-white w-[374px] h-[177px] bg-cover bg-no-repeat"></div>
        </Container>
    </div>
</template>

<style scoped>
    #colab1 {
        background-image: url('~/colab1.png');
        background-color: rgba(0,0,0, 0.2);
    }
    #colab2 {
        background-image: url('~/colab2.png');
        background-color: rgba(0,0,0, 0.2);
    }
    #colab3 {
        background-image: url('~/colab3.png');
        background-color: rgba(0,0,0, 0.2);
    }
    #colab4 {
        background-image: url('~/colab4.png');
        background-color: rgba(0,0,0, 0.2);
    }
    #colab5 {
        background-image: url('~/colab5.png');
        background-color: rgba(0,0,0, 0.2);
    }
    #colab6 {
        background-image: url('~/colab6.png');
        background-color: rgba(0,0,0, 0.2);
    }

</style>