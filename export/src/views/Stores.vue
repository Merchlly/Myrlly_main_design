
<template>
<main class="main">
    <div class="container">
        <div class="row row--grid">
            <!-- breadcrumb -->
            <div class="col-12">
                <ul class="breadcrumb">
                    <li class="breadcrumb__item">
                        <a href="index.html">Home</a>
                    </li>
                    <li class="breadcrumb__item breadcrumb__item--active">Authors</li>
                </ul>
            </div>
            <!-- end breadcrumb -->
            <!-- title -->
            <div class="col-12">
                <div class="main__title main__title--page">
                    <h1>Stores</h1>
                </div>
            </div>
            <!-- end title -->
            <!-- filter -->
            <div class="col-12">
                <div class="main__filter">
                    <form action="#" class="main__filter-search">
                        <input type="text" placeholder="Search for a creator…">
                        <button type="button">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                <path d="M21.71,20.29,18,16.61A9,9,0,1,0,16.61,18l3.68,3.68a1,1,0,0,0,1.42,0A1,1,0,0,0,21.71,20.29ZM11,18a7,7,0,1,1,7-7A7,7,0,0,1,11,18Z"/>
                            </svg>
                        </button>
                    </form>
                    <div class="main__filter-wrap">
                        <select class="main__select" name="status">
                            <option value="rating">By rating</option>
                            <option value="views">By views</option>
                            <option value="popularity">By popularity</option>
                        </select>
                        <select class="main__select" name="authors">
                            <option value="0">All Authors</option>
                            <option value="1">Verified only</option>
                        </select>
                    </div>
                </div>
            </div>
            <!-- end filter -->
        </div>
        <!-- authors -->
        <div class="row row--grid">
            <div class="col-12 col-sm-6 col-lg-4 col-xl-3">
                <div class="author">
                    <a href="author.html" class="author__cover author__cover--bg" data-bg="img/bg/bg-small.png"> </a>
                    <div class="author__meta">
                        <a href="author.html" class="author__avatar author__avatar--verified"> <img src="img/avatars/avatar.jpg" alt=""> </a>
                        <h3 class="author__name"><a href="author.html">Adam Zapel</a></h3>
                        <h3 class="author__nickname"><a href="author.html">@aaarthur</a></h3>
                        <p class="author__text">All the Lorem Ipsum generators on the Internet tend to repeat predefined chunks as necessary</p>
                        <div class="author__wrap">
                            <div class="author__followers">
                                <p>3829</p>
                                <span>Followers</span>
                            </div>
                            <button class="author__follow" type="button">Follow</button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-12 col-sm-6 col-lg-4 col-xl-3">
                <div class="author">
                    <a href="author.html" class="author__cover"> </a>
                    <div class="author__meta">
                        <a href="author.html" class="author__avatar author__avatar--verified"> <img src="img/avatars/avatar2.jpg" alt=""> </a>
                        <h3 class="author__name"><a href="author.html">Barb E. Dahl</a></h3>
                        <h3 class="author__nickname"><a href="author.html">@nicky87</a></h3>
                        <p class="author__text">If you are going to use a passage of Lorem Ipsum</p>
                        <div class="author__wrap">
                            <div class="author__followers">
                                <p>4602</p>
                                <span>Followers</span>
                            </div>
                            <button class="author__follow" type="button">Follow</button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-12 col-sm-6 col-lg-4 col-xl-3">
                <div class="author">
                    <a href="author.html" class="author__cover author__cover--bg" data-bg="img/bg/bg-small2.png"> </a>
                    <div class="author__meta">
                        <a href="author.html" class="author__avatar author__avatar--verified"> <img src="img/avatars/avatar3.jpg" alt=""> </a>
                        <h3 class="author__name"><a href="author.html">Biff Wellington</a></h3>
                        <h3 class="author__nickname"><a href="author.html">@neo</a></h3>
                        <p class="author__text">Many desktop publishing packages and web page editors now use Lorem</p>
                        <div class="author__wrap">
                            <div class="author__followers">
                                <p>1294</p>
                                <span>Followers</span>
                            </div>
                            <button class="author__follow author__follow--true" type="button">Unfollow</button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-12 col-sm-6 col-lg-4 col-xl-3">
                <div class="author">
                    <a href="author.html" class="author__cover author__cover--bg" data-bg="img/bg/bg-small3.png"> </a>
                    <div class="author__meta">
                        <a href="author.html" class="author__avatar author__avatar--verified"> <img src="img/avatars/avatar4.jpg" alt=""> </a>
                        <h3 class="author__name"><a href="author.html">Charity Case</a></h3>
                        <h3 class="author__nickname"><a href="author.html">@midinh</a></h3>
                        <p class="author__text">There are many variations of passages of Lorem Ipsum</p>
                        <div class="author__wrap">
                            <div class="author__followers">
                                <p>10 845</p>
                                <span>Followers</span>
                            </div>
                            <button class="author__follow" type="button">Follow</button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-12 col-sm-6 col-lg-4 col-xl-3">
                <div class="author">
                    <a href="author.html" class="author__cover"></a>
                    <div class="author__meta">
                        <a href="author.html" class="author__avatar author__avatar--verified"> <img src="img/avatars/avatar5.jpg" alt=""> </a>
                        <h3 class="author__name"><a href="author.html">Don Key</a></h3>
                        <h3 class="author__nickname"><a href="author.html">@kateblank</a></h3>
                        <p class="author__text">The generated Lorem Ipsum is therefore always free from repetition</p>
                        <div class="author__wrap">
                            <div class="author__followers">
                                <p>9713</p>
                                <span>Followers</span>
                            </div>
                            <button class="author__follow" type="button">Follow</button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-12 col-sm-6 col-lg-4 col-xl-3">
                <div class="author">
                    <a href="author.html" class="author__cover author__cover--bg" data-bg="img/bg/bg-small4.png"> </a>
                    <div class="author__meta">
                        <a href="author.html" class="author__avatar author__avatar--verified"> <img src="img/avatars/avatar6.jpg" alt=""> </a>
                        <h3 class="author__name"><a href="author.html">Mona Lott</a></h3>
                        <h3 class="author__nickname"><a href="author.html">@fantraingle</a></h3>
                        <p class="author__text">All the Lorem Ipsum generators on the Internet tend to repeat predefined chunks as necessary</p>
                        <div class="author__wrap">
                            <div class="author__followers">
                                <p>5 924</p>
                                <span>Followers</span>
                            </div>
                            <button class="author__follow" type="button">Follow</button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-12 col-sm-6 col-lg-4 col-xl-3">
                <div class="author">
                    <a href="author.html" class="author__cover author__cover--bg" data-bg="img/bg/bg-small5.png"> </a>
                    <div class="author__meta">
                        <a href="author.html" class="author__avatar"> <img src="img/avatars/avatar7.jpg" alt=""> </a>
                        <h3 class="author__name"><a href="author.html">Orson Carte</a></h3>
                        <h3 class="author__nickname"><a href="author.html">@sc00ty</a></h3>
                        <p class="author__text">It is a long established fact that a reader will be distracted</p>
                        <div class="author__wrap">
                            <div class="author__followers">
                                <p>11 342</p>
                                <span>Followers</span>
                            </div>
                            <button class="author__follow" type="button">Follow</button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-12 col-sm-6 col-lg-4 col-xl-3">
                <div class="author">
                    <a href="author.html" class="author__cover author__cover--bg" data-bg="img/bg/bg-small6.png"> </a>
                    <div class="author__meta">
                        <a href="author.html" class="author__avatar author__avatar--verified"> <img src="img/avatars/avatar8.jpg" alt=""> </a>
                        <h3 class="author__name"><a href="author.html">Ray Gunn</a></h3>
                        <h3 class="author__nickname"><a href="author.html">@justart</a></h3>
                        <p class="author__text">All the Lorem Ipsum generators on the Internet</p>
                        <div class="author__wrap">
                            <div class="author__followers">
                                <p>1245</p>
                                <span>Followers</span>
                            </div>
                            <button class="author__follow" type="button">Follow</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- end authors -->
        <!-- paginator -->
        <div class="row row--grid">
            <div class="col-12">
                <div class="paginator">
                    <span class="paginator__pages">8 from 169</span>
                    <ul class="paginator__list">
                        <li>
                            <a href="#"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                    <path d="M17,11H9.41l3.3-3.29a1,1,0,1,0-1.42-1.42l-5,5a1,1,0,0,0-.21.33,1,1,0,0,0,0,.76,1,1,0,0,0,.21.33l5,5a1,1,0,0,0,1.42,0,1,1,0,0,0,0-1.42L9.41,13H17a1,1,0,0,0,0-2Z"/>
                                </svg></a>
                        </li>
                        <li class="active">
                            <a href="#">1</a>
                        </li>
                        <li>
                            <a href="#">2</a>
                        </li>
                        <li>
                            <a href="#">3</a>
                        </li>
                        <li>
                            <a href="#">4</a>
                        </li>
                        <li>
                            <a href="#"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                    <path d="M17.92,11.62a1,1,0,0,0-.21-.33l-5-5a1,1,0,0,0-1.42,1.42L14.59,11H7a1,1,0,0,0,0,2h7.59l-3.3,3.29a1,1,0,0,0,0,1.42,1,1,0,0,0,1.42,0l5-5a1,1,0,0,0,.21-.33A1,1,0,0,0,17.92,11.62Z"/>
                                </svg></a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
        <!-- end paginator -->
    </div>
</main>
</template>
<script>
import mainHeader from "@/components/mainHeader.vue";
import mainFooter from "@/components/mainFooter.vue";

export default {
  name: "Stores",
  components:{
	mainHeader,
	mainFooter,
},
  data(){
      return { 
          }
      },
  created(){
    // Add logic on creation  
  },
  methods:{}  
}
</script>
<style>
</style>
