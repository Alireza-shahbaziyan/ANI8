<template>
    <div class="w-full  flex justify-center backdrop-blur-2xl flex-col items-center">
        <HeaderBox PartName="Wallpapers" />
        <div class="flex justify-around flex-wrap mt-8">
            <div v-for="item in animeList" :key="item.id" class="" >
                <div class="m-4 shadow-2xl">
                    <div class="relative h-40 w-56 flex justify-center items-center">
                        <img :src="item.banerImage" alt="Image" class="absolute w-full h-full rounded-xl">
                    <h3 class="text-white absolute font-semibold">{{item.animeName}}</h3>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import HeaderBox from './HeaderBox.vue';
export default {
    data() {
        return {
            Name: "wallpapers",
            animeList: [
                {id:1, animeName: 'demon slayer', banerImage: 'https://images.immediate.co.uk/production/volatile/sites/3/2022/10/MV5BOGZmYjkxMDItNmQ3ZC00YzdlLThjMDktYWJkOGZiOWU1NmY0XkEyXkFqcGdeQXVyMTA3MzQ4MTcw.V1-f69daeb.jpg' },
                {id:2, animeName: 'demon slayer2', banerImage: 'https://images.immediate.co.uk/production/volatile/sites/3/2022/10/MV5BOGZmYjkxMDItNmQ3ZC00YzdlLThjMDktYWJkOGZiOWU1NmY0XkEyXkFqcGdeQXVyMTA3MzQ4MTcw.V1-f69daeb.jpg' },
                {id:3, animeName: 'demon slayer3', banerImage: 'https://images.immediate.co.uk/production/volatile/sites/3/2022/10/MV5BOGZmYjkxMDItNmQ3ZC00YzdlLThjMDktYWJkOGZiOWU1NmY0XkEyXkFqcGdeQXVyMTA3MzQ4MTcw.V1-f69daeb.jpg' },
                {id:3, animeName: 'demon slayer3', banerImage: 'https://images.immediate.co.uk/production/volatile/sites/3/2022/10/MV5BOGZmYjkxMDItNmQ3ZC00YzdlLThjMDktYWJkOGZiOWU1NmY0XkEyXkFqcGdeQXVyMTA3MzQ4MTcw.V1-f69daeb.jpg' },
                {id:3, animeName: 'demon slayer3', banerImage: 'https://images.immediate.co.uk/production/volatile/sites/3/2022/10/MV5BOGZmYjkxMDItNmQ3ZC00YzdlLThjMDktYWJkOGZiOWU1NmY0XkEyXkFqcGdeQXVyMTA3MzQ4MTcw.V1-f69daeb.jpg' },
                {id:3, animeName: 'demon slayer3', banerImage: 'https://images.immediate.co.uk/production/volatile/sites/3/2022/10/MV5BOGZmYjkxMDItNmQ3ZC00YzdlLThjMDktYWJkOGZiOWU1NmY0XkEyXkFqcGdeQXVyMTA3MzQ4MTcw.V1-f69daeb.jpg' },
                {id:3, animeName: 'demon slayer3', banerImage: 'https://images.immediate.co.uk/production/volatile/sites/3/2022/10/MV5BOGZmYjkxMDItNmQ3ZC00YzdlLThjMDktYWJkOGZiOWU1NmY0XkEyXkFqcGdeQXVyMTA3MzQ4MTcw.V1-f69daeb.jpg' },
                {id:3, animeName: 'demon slayer3', banerImage: 'https://images.immediate.co.uk/production/volatile/sites/3/2022/10/MV5BOGZmYjkxMDItNmQ3ZC00YzdlLThjMDktYWJkOGZiOWU1NmY0XkEyXkFqcGdeQXVyMTA3MzQ4MTcw.V1-f69daeb.jpg' },
                {id:3, animeName: 'demon slayer3', banerImage: 'https://images.immediate.co.uk/production/volatile/sites/3/2022/10/MV5BOGZmYjkxMDItNmQ3ZC00YzdlLThjMDktYWJkOGZiOWU1NmY0XkEyXkFqcGdeQXVyMTA3MzQ4MTcw.V1-f69daeb.jpg' },
                {id:3, animeName: 'demon slayer3', banerImage: 'https://images.immediate.co.uk/production/volatile/sites/3/2022/10/MV5BOGZmYjkxMDItNmQ3ZC00YzdlLThjMDktYWJkOGZiOWU1NmY0XkEyXkFqcGdeQXVyMTA3MzQ4MTcw.V1-f69daeb.jpg' },
                {id:3, animeName: 'demon slayer3', banerImage: 'https://images.immediate.co.uk/production/volatile/sites/3/2022/10/MV5BOGZmYjkxMDItNmQ3ZC00YzdlLThjMDktYWJkOGZiOWU1NmY0XkEyXkFqcGdeQXVyMTA3MzQ4MTcw.V1-f69daeb.jpg' },
                {id:3, animeName: 'demon slayer3', banerImage: 'https://images.immediate.co.uk/production/volatile/sites/3/2022/10/MV5BOGZmYjkxMDItNmQ3ZC00YzdlLThjMDktYWJkOGZiOWU1NmY0XkEyXkFqcGdeQXVyMTA3MzQ4MTcw.V1-f69daeb.jpg' },
                {id:3, animeName: 'demon slayer3', banerImage: 'https://images.immediate.co.uk/production/volatile/sites/3/2022/10/MV5BOGZmYjkxMDItNmQ3ZC00YzdlLThjMDktYWJkOGZiOWU1NmY0XkEyXkFqcGdeQXVyMTA3MzQ4MTcw.V1-f69daeb.jpg' },
            ]
        }
    },
    components: {
        HeaderBox
    }
}
</script>