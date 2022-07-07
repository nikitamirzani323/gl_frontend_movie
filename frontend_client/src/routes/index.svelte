<script>
    let listmovie = [
        {idmovie:"123123",nmmovie:"The Flash",urlimage:"https://s5.indexmovies.xyz/wp-content/uploads/2021/11/film-the-flash-2014-lk21-d21.jpg"},
        {idmovie:"123123",nmmovie:"Sonic",urlimage:"https://s2.indexmovies.xyz/wp-content/uploads/2022/05/film-sonic-the-hedgehog-2-2022-lk21-d21.jpg"},
        {idmovie:"123123",nmmovie:"Superman",urlimage:"https://s6.indexmovies.xyz/wp-content/uploads/2022/01/film-superman-and-lois-superman-lois-2021-lk21-d21.jpg"},
        {idmovie:"123123",nmmovie:"Space Bow",urlimage:"https://s3.indexmovies.xyz/wp-content/uploads/2015/12/film-space-cowboys-2000.jpg"},
        {idmovie:"123123",nmmovie:"Hometow",urlimage:"https://s7.indexmovies.xyz/wp-content/uploads/2021/11/film-hometown-cha-cha-cha-gaetmaeul-chachacha-2021-d21.jpg"},
        {idmovie:"123123",nmmovie:"The Falcon",urlimage:"https://s0.indexmovies.xyz/wp-content/uploads/2021/11/film-the-falcon-and-the-winter-soldier-2021-d21.jpg"},
        {idmovie:"123123",nmmovie:"The Pirates: The Last Royal Treasure (2022)",urlimage:"https://s5.indexmovies.xyz/wp-content/uploads/2022/03/film-the-pirates-the-last-royal-treasure-2022-lk21-d21.jpg"},
        {idmovie:"123123",nmmovie:"Doctor Stranger",urlimage:"https://s6.indexmovies.xyz/wp-content/uploads/2022/05/film-doctor-strange-in-the-multiverse-of-madness-2022-lk21-d21.jpg"},
    ]
</script>

<section class="card w-full bg-base-300 text-neutral-content rounded-none mt-5">
    <div class="card-body p-0 mb-2">
        <h2 class="card-title border-b-2 border-pink-700 p-2">LK21 MOVIE TERBARU</h2>
        <div class="grid grid-cols-2 lg:grid-cols-8 gap-2 p-2">
            {#each listmovie as rec}
            <div class="flex flex-col cursor-pointer w-full justify-items-center mb-1">
                <div class="absolute">
                    <div class="flex mt-0 bg-black p-1 opacity-90 w-12">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-yellow-300" viewBox="0 0 20 20" fill="currentColor">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                        </svg>
                        <span class=" text-sm">5.2</span>
                    </div>
                </div>
                <img
                    class="w-full" 
                    src="{rec.urlimage}" alt="">
                <div class="flex flex-col h-20 w-full justify-between -mt-20">
                    <span class="">&nbsp;</span>
                    <span class="w-full self-end text-center hidden lg:block lg:text-xs">{rec.nmmovie}</span>
                </div>
            </div>
            {/each}
        </div>
        <div class="w-full text-center">
            <button class="btn btn-primary btn-sm">Tampilkan Semua</button>
        </div>
    </div>
</section>

<section class="card w-full bg-base-300 text-neutral-content rounded-none mt-5">
    <div class="card-body p-0 mb-2">
        <h2 class="card-title border-b-2 border-pink-700 p-2">LK21 MOVIE TERBARU</h2>
        <div class="grid grid-cols-2 lg:grid-cols-8 gap-2 p-2">
            {#each listmovie as rec}
            <div class="flex flex-col cursor-pointer w-full justify-items-center mb-1">
                <div class="absolute">
                    <div class="flex mt-0 bg-black p-1 opacity-90 w-12">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-yellow-300" viewBox="0 0 20 20" fill="currentColor">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                        </svg>
                        <span class=" text-sm">5.2</span>
                    </div>
                </div>
                <img
                    class="w-full" 
                    src="{rec.urlimage}" alt="">
                <div class="flex flex-col h-20 w-full justify-between -mt-20">
                    <span class="">&nbsp;</span>
                    <span class="w-full self-end text-center hidden lg:block lg:text-xs">{rec.nmmovie}</span>
                </div>
            </div>
            {/each}
        </div>
        <div class="w-full text-center">
            <button class="btn btn-primary btn-sm">Tampilkan Semua</button>
        </div>
    </div>
</section>