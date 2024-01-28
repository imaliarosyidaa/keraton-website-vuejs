<template>
  <div class="object-wisata">
    <div class="about">Object Wisata</div>
    <div class="about-title">Keraton Kasepuhan Cirebon</div>
    <div class="bg-orange">
        <div class="event-text">
            <p>Pada awal pembangunannya, Keraton Kasepuhan dibangun oleh Pangeran Emas Zainul Arifin dengan maksud untuk memperluas bangunan pesanggerahan Keraton Pangkuwati.</p>
        </div>
        <div class="btn-white">
        <a>Beli Tiket Sekarang</a>
        <div class="btn-icon">
            <svg xmlns="http://www.w3.org/2000/svg" width="34" height="34" viewBox="0 0 34 34" fill="none">
            <g clip-path="url(#clip0_119_991)">
                <path d="M24.0002 10.2146C22.6647 8.82355 20.9467 7.85978 19.0634 7.44516C17.1801 7.03054 15.2162 7.18368 13.42 7.88522C11.6238 8.58676 10.0759 9.80519 8.97215 11.3864C7.86839 12.9677 7.25831 14.8407 7.21907 16.7687C7.17982 18.6966 7.71316 20.593 8.75165 22.2178C9.79014 23.8427 11.2871 25.1231 13.0533 25.8971C14.8195 26.6712 16.7756 26.9041 18.6741 26.5665C20.5727 26.2289 22.3286 25.3358 23.7196 24.0003C25.5824 22.208 26.6581 19.75 26.7108 17.1655C26.7634 14.581 25.7886 12.0812 24.0002 10.2146ZM18.4821 20.711C18.3387 20.8488 18.1463 20.9239 17.9475 20.9199C17.7486 20.9158 17.5595 20.8329 17.4217 20.6895C17.2839 20.546 17.2088 20.3536 17.2129 20.1548C17.2169 19.9559 17.2998 19.7668 17.4433 19.629L19.3835 17.7662L12.71 17.631C12.6115 17.629 12.5143 17.6076 12.4241 17.5681C12.3338 17.5285 12.2522 17.4716 12.184 17.4005C12.1157 17.3294 12.0621 17.2456 12.0263 17.1538C11.9904 17.062 11.973 16.964 11.975 16.8655C11.977 16.767 11.9984 16.6698 12.038 16.5795C12.0775 16.4893 12.1345 16.4077 12.2056 16.3395C12.2767 16.2712 12.3605 16.2176 12.4523 16.1818C12.5441 16.1459 12.642 16.1285 12.7406 16.1305L19.414 16.267L17.5512 14.3268C17.4135 14.1833 17.3384 13.991 17.3424 13.7921C17.3465 13.5933 17.4293 13.4041 17.5728 13.2664C17.7163 13.1286 17.9086 13.0535 18.1075 13.0575C18.3064 13.0616 18.4955 13.1445 18.6333 13.288L21.7498 16.534C21.8876 16.6775 21.9627 16.8699 21.9586 17.0687C21.9546 17.2676 21.8717 17.4567 21.7282 17.5945L18.4821 20.711Z" fill="#212121"/>
            </g>
            <defs>
                <clipPath id="clip0_119_991">
                <rect width="24" height="24" fill="white" transform="translate(17.3124) rotate(46.1662)"/>
                </clipPath>
            </defs>
            </svg>
        </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'ObjectWisata'
}
</script>

<style>
    #object-wisata{
        margin-top: 131 px;
    }
    .bg-orange{
        margin-top: 58px;
        background: #DAA520;
        width: 100%;
        height: fit-content;
        padding: 98px 0 98px 93px;
    }
    .btn-white{
        width: fit-content;
        margin-top: 44px;
        padding: 0 5px 0 5px;
        border-radius: 10px;
        background: var(--primary, white);
        box-shadow: 4px 4px 4px 0px rgba(0, 0, 0, 0.25);
        display: flex;
        align-content: center;
    }
    .btn-white a{
        display: flex;
        align-items: center;
    }
    .btn-icon{
        display: flex;
        align-content: center;
    }
    .event-text p{
        width: 557px;
        color: #000;
        /* Raleway/regular/h6 */
        font-family: Raleway;
        font-size: 20px;
        font-style: normal;
        font-weight: 400;
        line-height: 28px; 
    }
</style>