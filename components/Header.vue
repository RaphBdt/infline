<template>
    <div class="bg-black h-[682px] pt-6">
        <Logo class="text-center" color="white" />
        <Container class="flex mt-36">
            <div class="w-1/2">
                <HomeTitle content="La plateforme n°1 pour trouver un" specialWord="Influenceur" /> 
                <div class="flex mt-12">
                    <Button class="mr-8" content="Je suis influenceur" link="/" type="white" />
                    <Button content="Je suis une marque" link="/" type="primary" />
                </div>
            </div>
            <div class="w-1/2 flex justify-end">
                <img class="w-3/4 object-cover h-[550px]" src="~/assets/images/selfie.jpg" alt="Selfie">
            </div>
        </Container>
    </div>
</template>