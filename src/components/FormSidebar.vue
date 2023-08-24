<template lang="">
    <div>
        <form class="max-w-md w-5/12 shadow-lg px-32 overflow-y-scroll bg-white dark:bg-dm-shade-darkest" style="min-width: 300px;">




<div class="flex flex-col my-32">
    <div class="flex justify-between items-end">
        <label for="top-mark" class="pb-8 font-sansUI leading-normal text-s text-black dark:text-shade-lightest">Dachzeile</label>
       
    </div>
    <div class="group relative flex flex-col">
        <input class="peer appearance-none rounded placeholder-shade-base dark:disabled:placeholder-shade-dark outline-focus disabled:cursor-not-allowed p-12 font-sansUI leading-normal text-black dark:text-shade-lightest text-base bg-white dark:bg-shade-darkest dark:disabled:bg-dm-shade-darkest border border-shade-base hover:border-black disabled:border-shade-lighter dark:border-shade-light dark:hover:border-shade-lightest dark:disabled:border-shade-dark autofill:transition-colors autofill:duration-max" id="top-mark" name="top-mark" x-model="$store.templateData.topMark" placeholder="Dachzeile eingeben..." @keyup.ctrl.shift.-.prevent="$insertIntoModelAtCursorPosition('\u00AD')">
    </div>
</div>

<div class="flex flex-col my-32">
    <div class="flex justify-between items-end">
        <label for="headline" class="pb-8 font-sansUI leading-normal text-s text-black dark:text-shade-lightest">Überschrift</label>
        <div class="relative w-16 h-16 my-6 hover:cursor-pointer flex items-center justify-center border border-shade-lighter hover:border-shade-light rounded-circle text-shade-base group">
            <svg width="12" height="12"><use xlink:href="#info"></use></svg>
           
        </div>
    </div>
    <div class="group relative flex flex-col">
        <input class="peer appearance-none rounded placeholder-shade-base dark:disabled:placeholder-shade-dark outline-focus disabled:cursor-not-allowed p-12 font-sansUI leading-normal text-black dark:text-shade-lightest text-base bg-white dark:bg-shade-darkest dark:disabled:bg-dm-shade-darkest border border-shade-base hover:border-black disabled:border-shade-lighter dark:border-shade-light dark:hover:border-shade-lightest dark:disabled:border-shade-dark autofill:transition-colors autofill:duration-max" id="headline" name="headline" x-model="$store.templateData.headline" placeholder="Überschrift eingeben..." @keyup.ctrl.shift.-.prevent="$insertIntoModelAtCursorPosition('\u00AD')">
    </div>
</div>

<div class="flex flex-col my-32">
    <div class="flex justify-between items-end">
        <label for="description" class="pb-8 font-sansUI leading-normal text-s text-black dark:text-shade-lightest">Beschreibung</label>
        <div class="relative w-16 h-16 my-6 hover:cursor-pointer flex items-center justify-center border border-shade-lighter hover:border-shade-light rounded-circle text-shade-base group">
            <svg width="12" height="12"><use xlink:href="#info"></use></svg>

        </div>
    </div>
    <div class="group relative flex flex-col">
        <input class="peer appearance-none rounded placeholder-shade-base dark:disabled:placeholder-shade-dark outline-focus disabled:cursor-not-allowed p-12 font-sansUI leading-normal text-black dark:text-shade-lightest text-base bg-white dark:bg-shade-darkest dark:disabled:bg-dm-shade-darkest border border-shade-base hover:border-black disabled:border-shade-lighter dark:border-shade-light dark:hover:border-shade-lightest dark:disabled:border-shade-dark autofill:transition-colors autofill:duration-max" id="description" name="description" x-model="$store.templateData.description" placeholder="Beschreibung eingeben..." @keyup.ctrl.shift.-.prevent="$insertIntoModelAtCursorPosition('\u00AD')">
    </div>
</div>

<div class="flex flex-col my-32">
    <div class="flex justify-between items-end">
        <label for="additional-info" class="pb-8 font-sansUI leading-normal text-s text-black dark:text-shade-lightest">Zusatzinfo</label>
        <div class="relative w-16 h-16 my-6 hover:cursor-pointer flex items-center justify-center border border-shade-lighter hover:border-shade-light rounded-circle text-shade-base group">
    
        </div>
    </div>
    <div class="group relative flex flex-col">
        <input class="peer appearance-none rounded placeholder-shade-base dark:disabled:placeholder-shade-dark outline-focus disabled:cursor-not-allowed p-12 font-sansUI leading-normal text-black dark:text-shade-lightest text-base bg-white dark:bg-shade-darkest dark:disabled:bg-dm-shade-darkest border border-shade-base hover:border-black disabled:border-shade-lighter dark:border-shade-light dark:hover:border-shade-lightest dark:disabled:border-shade-dark autofill:transition-colors autofill:duration-max" id="additional-info" name="additional-info" x-model="$store.templateData.additionalInfo" placeholder="Zusatzinfo eingeben..." @keyup.ctrl.shift.-.prevent="$insertIntoModelAtCursorPosition('\u00AD')">
    </div>
</div>

<div class="flex flex-col my-32">
    <label for="url" class="pb-8 font-sansUI leading-normal text-s text-black dark:text-shade-lightest">Link</label>
    <div class="group relative flex flex-col">
        <input class="peer appearance-none rounded placeholder-shade-base dark:disabled:placeholder-shade-dark outline-focus disabled:cursor-not-allowed pl-12 pr-48 py-12 font-sansUI leading-normal text-black dark:text-shade-lightest text-base bg-white dark:bg-shade-darkest dark:disabled:bg-dm-shade-darkest border border-shade-base hover:border-black disabled:border-shade-lighter dark:border-shade-light dark:hover:border-shade-lightest dark:disabled:border-shade-dark autofill:transition-colors autofill:duration-max" id="url" name="url" x-model="$store.templateData.url" placeholder="https://...">
        <span class="absolute top-0 bottom-0 right-0 pr-12 pointer-events-none flex items-center text-shade-darker dark:text-shade-lightest group-hover:text-shade-darkest dark:group-hover:text-shade-lightest peer-disabled:text-shade-base dark:peer-disabled:text-shade-dark">
            <svg width="24" height="24"><use xlink:href="#link"></use></svg>
        </span>
    </div>
</div>


<div class="flex flex-col my-32">
    <label for="image-large-url" class="pb-8 font-sansUI leading-normal text-s text-black dark:text-shade-lightest">Bild groß</label>
    <div class="group relative flex flex-col">
        <input class="peer appearance-none rounded placeholder-shade-base dark:disabled:placeholder-shade-dark outline-focus disabled:cursor-not-allowed pl-12 pr-48 py-12 font-sansUI leading-normal text-black dark:text-shade-lightest text-base bg-white dark:bg-shade-darkest dark:disabled:bg-dm-shade-darkest border border-shade-base hover:border-black disabled:border-shade-lighter dark:border-shade-light dark:hover:border-shade-lightest dark:disabled:border-shade-dark autofill:transition-colors autofill:duration-max" id="image-large-url" name="image-large-url" x-model="$store.templateData.imageLarge.url" placeholder="https://interactive.spiegel.de/...">
        <span class="absolute top-0 bottom-0 right-0 pr-12 pointer-events-none flex items-center text-shade-darker dark:text-shade-lightest group-hover:text-shade-darkest dark:group-hover:text-shade-lightest peer-disabled:text-shade-base dark:peer-disabled:text-shade-dark">
            <svg width="24" height="24"><use xlink:href="#photo"></use></svg>
        </span>
    </div>
</div>

<div class="flex flex-col my-32">
    <label for="image-large-credit" class="pb-8 font-sansUI leading-normal text-s text-black dark:text-shade-lightest">Bildcredit groß</label>
    <div class="group relative flex flex-col">
        <input class="peer appearance-none rounded placeholder-shade-base dark:disabled:placeholder-shade-dark outline-focus disabled:cursor-not-allowed p-12 font-sansUI leading-normal text-black dark:text-shade-lightest text-base bg-white dark:bg-shade-darkest dark:disabled:bg-dm-shade-darkest border border-shade-base hover:border-black disabled:border-shade-lighter dark:border-shade-light dark:hover:border-shade-lightest dark:disabled:border-shade-dark autofill:transition-colors autofill:duration-max" id="image-large-credit" name="image-large-credit" x-model="$store.templateData.imageLarge.credit" placeholder="Bildcredit eingeben...">
    </div>
</div>

<div class="flex flex-col my-32">
    <label for="image-small-url" class="pb-8 font-sansUI leading-normal text-s text-black dark:text-shade-lightest">Bild klein</label>
    <div class="group relative flex flex-col">
        <input class="peer appearance-none rounded placeholder-shade-base dark:disabled:placeholder-shade-dark outline-focus disabled:cursor-not-allowed pl-12 pr-48 py-12 font-sansUI leading-normal text-black dark:text-shade-lightest text-base bg-white dark:bg-shade-darkest dark:disabled:bg-dm-shade-darkest border border-shade-base hover:border-black disabled:border-shade-lighter dark:border-shade-light dark:hover:border-shade-lightest dark:disabled:border-shade-dark autofill:transition-colors autofill:duration-max" id="image-small-url" name="image-small-url" x-model="$store.templateData.imageSmall.url" placeholder="https://interactive.spiegel.de/...">
        <span class="absolute top-0 bottom-0 right-0 pr-12 pointer-events-none flex items-center text-shade-darker dark:text-shade-lightest group-hover:text-shade-darkest dark:group-hover:text-shade-lightest peer-disabled:text-shade-base dark:peer-disabled:text-shade-dark">
            <svg width="24" height="24"><use xlink:href="#photo"></use></svg>
        </span>
    </div>
</div>

<div class="flex flex-col my-32">
    <label for="image-small-credit" class="pb-8 font-sansUI leading-normal text-s text-black dark:text-shade-lightest">Bildcredit klein</label>
    <div class="group relative flex flex-col">
        <input class="peer appearance-none rounded placeholder-shade-base dark:disabled:placeholder-shade-dark outline-focus disabled:cursor-not-allowed p-12 font-sansUI leading-normal text-black dark:text-shade-lightest text-base bg-white dark:bg-shade-darkest dark:disabled:bg-dm-shade-darkest border border-shade-base hover:border-black disabled:border-shade-lighter dark:border-shade-light dark:hover:border-shade-lightest dark:disabled:border-shade-dark autofill:transition-colors autofill:duration-max" id="image-small-credit" name="image-small-credit" x-model="$store.templateData.imageSmall.credit" placeholder="Bildcredit eingeben...">
    </div>
</div>

<hr class="border-0 h-px border-separator-b my-32">

<div class="flex flex-col my-32">
    <label for="cta-primary-url" class="pb-8 font-sansUI leading-normal text-s text-black dark:text-shade-lightest">Primary Button Link</label>
    <div class="group relative flex flex-col">
        <input class="peer appearance-none rounded placeholder-shade-base dark:disabled:placeholder-shade-dark outline-focus disabled:cursor-not-allowed pl-12 pr-48 py-12 font-sansUI leading-normal text-black dark:text-shade-lightest text-base bg-white dark:bg-shade-darkest dark:disabled:bg-dm-shade-darkest border border-shade-base hover:border-black disabled:border-shade-lighter dark:border-shade-light dark:hover:border-shade-lightest dark:disabled:border-shade-dark autofill:transition-colors autofill:duration-max" id="cta-primary-url" name="cta-primary-url" x-model="$store.templateData.ctaPrimary.url" placeholder="https://...">
        <span class="absolute top-0 bottom-0 right-0 pr-12 pointer-events-none flex items-center text-shade-darker dark:text-shade-lightest group-hover:text-shade-darkest dark:group-hover:text-shade-lightest peer-disabled:text-shade-base dark:peer-disabled:text-shade-dark">
            <svg width="24" height="24"><use xlink:href="#link"></use></svg>
        </span>
    </div>
</div>

<div class="flex flex-col my-32">
    <label for="cta-primary-label" class="pb-8 font-sansUI leading-normal text-s text-black dark:text-shade-lightest">Primary Button Label</label>
    <div class="group relative flex flex-col">
        <input class="peer appearance-none rounded placeholder-shade-base dark:disabled:placeholder-shade-dark outline-focus disabled:cursor-not-allowed p-12 font-sansUI leading-normal text-black dark:text-shade-lightest text-base bg-white dark:bg-shade-darkest dark:disabled:bg-dm-shade-darkest border border-shade-base hover:border-black disabled:border-shade-lighter dark:border-shade-light dark:hover:border-shade-lightest dark:disabled:border-shade-dark autofill:transition-colors autofill:duration-max" id="cta-primary-label" name="cta-primary-label" x-model="$store.templateData.ctaPrimary.label" placeholder="Label eingeben...">
    </div>
</div>

<div class="flex flex-col my-32">
    <label for="cta-secondary-url" class="pb-8 font-sansUI leading-normal text-s text-black dark:text-shade-lightest">Secondary Button Link</label>
    <div class="group relative flex flex-col">
        <input class="peer appearance-none rounded placeholder-shade-base dark:disabled:placeholder-shade-dark outline-focus disabled:cursor-not-allowed pl-12 pr-48 py-12 font-sansUI leading-normal text-black dark:text-shade-lightest text-base bg-white dark:bg-shade-darkest dark:disabled:bg-dm-shade-darkest border border-shade-base hover:border-black disabled:border-shade-lighter dark:border-shade-light dark:hover:border-shade-lightest dark:disabled:border-shade-dark autofill:transition-colors autofill:duration-max" id="cta-secondary-url" name="cta-secondary-url" x-model="$store.templateData.ctaSecondary.url" placeholder="https://...">
        <span class="absolute top-0 bottom-0 right-0 pr-12 pointer-events-none flex items-center text-shade-darker dark:text-shade-lightest group-hover:text-shade-darkest dark:group-hover:text-shade-lightest peer-disabled:text-shade-base dark:peer-disabled:text-shade-dark">
            <svg width="24" height="24"><use xlink:href="#link"></use></svg>
        </span>
    </div>
</div>

<div class="flex flex-col my-32">
    <label for="cta-secondary-label" class="pb-8 font-sansUI leading-normal text-s text-black dark:text-shade-lightest">Secondary Button Label</label>
    <div class="group relative flex flex-col">
        <input class="peer appearance-none rounded placeholder-shade-base dark:disabled:placeholder-shade-dark outline-focus disabled:cursor-not-allowed p-12 font-sansUI leading-normal text-black dark:text-shade-lightest text-base bg-white dark:bg-shade-darkest dark:disabled:bg-dm-shade-darkest border border-shade-base hover:border-black disabled:border-shade-lighter dark:border-shade-light dark:hover:border-shade-lightest dark:disabled:border-shade-dark autofill:transition-colors autofill:duration-max" id="cta-secondary-label" name="cta-secondary-label" x-model="$store.templateData.ctaSecondary.label" placeholder="Label eingeben...">
    </div>
</div>

</form>
    </div>
</template>
<script>
export default {

}
</script>
<style lang="">
    
</style>