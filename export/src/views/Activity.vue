
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
                    <li class="breadcrumb__item breadcrumb__item--active">Activity</li>
                </ul>
            </div>
            <!-- end breadcrumb -->
            <!-- title -->
            <div class="col-12">
                <div class="main__title main__title--page">
                    <h1>Activity</h1>
                </div>
            </div>
            <!-- end title -->
        </div>
        <div class="row">
            <!-- sidebar -->
            <div class="col-12 col-xl-3 order-xl-2">
                <div class="filter-wrap">
                    <button class="filter-wrap__btn" type="button" data-toggle="collapse" data-target="#collapseFilter" aria-expanded="false" aria-controls="collapseFilter">Open filter</button>
                    <div class="collapse filter-wrap__content" id="collapseFilter">
                        <!-- filter -->
                        <div class="filter filter--sticky">
                            <h4 class="filter__title">Filters <button type="button">Clear all</button></h4>
                            <div class="filter__group">
                                <ul class="filter__checkboxes">
                                    <li>
                                        <input id="type5" type="checkbox" name="type5" checked="">
                                        <label for="type5">Listings</label>
                                    </li>
                                    <li>
                                        <input id="type6" type="checkbox" name="type6">
                                        <label for="type6">Purchases</label>
                                    </li>
                                    <li>
                                        <input id="type7" type="checkbox" name="type7" checked="">
                                        <label for="type7">Sales</label>
                                    </li>
                                    <li>
                                        <input id="type8" type="checkbox" name="type8" checked="">
                                        <label for="type8">Transfers</label>
                                    </li>
                                    <li class="d-none">
                                        <input id="type9" type="checkbox" name="type9">
                                        <label for="type9">Bids</label>
                                    </li>
                                    <li>
                                        <input id="type10" type="checkbox" name="type10">
                                        <label for="type10">Likes</label>
                                    </li>
                                    <li>
                                        <input id="type11" type="checkbox" name="type11">
                                        <label for="type11">Followings</label>
                                    </li>
                                </ul>
                            </div>
                        </div>
                        <!-- end filter -->
                    </div>
                </div>
            </div>
            <!-- end sidebar -->
            <!-- content -->
            <div class="col-12 col-xl-9 order-xl-1">
                <div class="row row--grid">
                    <div class="col-12 col-lg-6">
                        <div class="activity">
                            <a href="item.html" class="activity__cover"> <img src="img/cover/cover1.jpg" alt=""> </a>
                            <div class="activity__content">
                                <h3 class="activity__title"><a href="item.html">Walking on Air</a></h3>
                                <p class="activity__text">listed by <a href="author.html">@Nickname</a> <br>for <b>0.049 NGN</b></p>
                                <span class="activity__time">4 minutes ago</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6">
                        <div class="activity">
                            <a href="item.html" class="activity__cover"> <img src="img/cover/cover2.jpg" alt=""> </a>
                            <div class="activity__content">
                                <h3 class="activity__title"><a href="item.html">To Infinity And Beyond</a></h3>
                                <p class="activity__text">9 editions listed by <a href="author.html">@neo</a> <br>for <b>0.085 NGN</b> each</p>
                                <span class="activity__time">21 minutes ago</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6">
                        <div class="activity">
                            <a href="item.html" class="activity__cover"> <img src="img/cover/cover3.jpg" alt=""> </a>
                            <div class="activity__content">
                                <h3 class="activity__title"><a href="item.html">Flowers in Concrete</a></h3>
                                <p class="activity__text">purchased by <a href="author.html">@johndoe</a> <b>0x23d2dc92b...82c6</b> for <b>0.011 NGN</b> from <a href="author.html">@min1max</a></p>
                                <span class="activity__time">21 minutes ago</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6">
                        <div class="activity">
                            <a href="item.html" class="activity__cover"> <img src="img/cover/cover4.jpg" alt=""> </a>
                            <div class="activity__content">
                                <h3 class="activity__title"><a href="item.html">Industrial Revolution</a></h3>
                                <p class="activity__text">transferred from <a href="author.html">@midinh</a> <br>to <a href="author.html">@johndoe</a></p>
                                <span class="activity__time">23 minutes ago</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6">
                        <div class="activity">
                            <a href="item.html" class="activity__cover"> <img src="img/cover/cover5.jpg" alt=""> </a>
                            <div class="activity__content">
                                <h3 class="activity__title"><a href="item.html">Tranquility</a></h3>
                                <p class="activity__text"><a href="author.html">@aaarthur</a> offered <b>0.002 WNGN</b></p>
                                <span class="activity__time">41 minutes ago</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6">
                        <div class="activity">
                            <a href="item.html" class="activity__cover"> <img src="img/cover/cover6.jpg" alt=""> </a>
                            <div class="activity__content">
                                <h3 class="activity__title"><a href="item.html">Tetradecapus</a></h3>
                                <p class="activity__text">liked by <a href="author.html">@johndoe</a></p>
                                <span class="activity__time">45 minutes ago</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6">
                        <div class="activity">
                            <a href="item.html" class="activity__cover"> <img src="img/cover/cover7.jpg" alt=""> </a>
                            <div class="activity__content">
                                <h3 class="activity__title"><a href="item.html">Elegance</a></h3>
                                <p class="activity__text">started following <a href="author.html">@johndoe</a></p>
                                <span class="activity__time">48 minutes ago</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6">
                        <div class="activity">
                            <a href="item.html" class="activity__cover"> <img src="img/cover/cover8.jpg" alt=""> </a>
                            <div class="activity__content">
                                <h3 class="activity__title"><a href="item.html">Walking on Air</a></h3>
                                <p class="activity__text">started following <a href="author.html">@johndoe</a></p>
                                <span class="activity__time">49 minutes ago</span>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- collapse -->
                <div class="row row--grid collapse" id="collapsemore">
                    <div class="col-12 col-lg-6">
                        <div class="activity">
                            <a href="item.html" class="activity__cover"> <img src="img/cover/cover1.jpg" alt=""> </a>
                            <div class="activity__content">
                                <h3 class="activity__title"><a href="item.html">Walking on Air</a></h3>
                                <p class="activity__text">listed by <a href="author.html">@Nickname</a> <br>for <b>0.049 NGN</b></p>
                                <span class="activity__time">4 minutes ago</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6">
                        <div class="activity">
                            <a href="item.html" class="activity__cover"> <img src="img/cover/cover2.jpg" alt=""> </a>
                            <div class="activity__content">
                                <h3 class="activity__title"><a href="item.html">To Infinity And Beyond</a></h3>
                                <p class="activity__text">9 editions listed by <a href="author.html">@neo</a> <br>for <b>0.085 NGN</b> each</p>
                                <span class="activity__time">21 minutes ago</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6">
                        <div class="activity">
                            <a href="item.html" class="activity__cover"> <img src="img/cover/cover3.jpg" alt=""> </a>
                            <div class="activity__content">
                                <h3 class="activity__title"><a href="item.html">Flowers in Concrete</a></h3>
                                <p class="activity__text">purchased by <a href="author.html">@johndoe</a> <b>0x23d2dc92b...82c6</b> for <b>0.011 NGN</b> from <a href="author.html">@min1max</a></p>
                                <span class="activity__time">21 minutes ago</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6">
                        <div class="activity">
                            <a href="item.html" class="activity__cover"> <img src="img/cover/cover4.jpg" alt=""> </a>
                            <div class="activity__content">
                                <h3 class="activity__title"><a href="item.html">Industrial Revolution</a></h3>
                                <p class="activity__text">transferred from <a href="author.html">@midinh</a> <br>to <a href="author.html">@johndoe</a></p>
                                <span class="activity__time">23 minutes ago</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6">
                        <div class="activity">
                            <a href="item.html" class="activity__cover"> <img src="img/cover/cover5.jpg" alt=""> </a>
                            <div class="activity__content">
                                <h3 class="activity__title"><a href="item.html">Tranquility</a></h3>
                                <p class="activity__text"><a href="author.html">@aaarthur</a> offered <b>0.002 WNGN</b></p>
                                <span class="activity__time">41 minutes ago</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6">
                        <div class="activity">
                            <a href="item.html" class="activity__cover"> <img src="img/cover/cover6.jpg" alt=""> </a>
                            <div class="activity__content">
                                <h3 class="activity__title"><a href="item.html">Tetradecapus</a></h3>
                                <p class="activity__text">liked by <a href="author.html">@johndoe</a></p>
                                <span class="activity__time">45 minutes ago</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6">
                        <div class="activity">
                            <a href="item.html" class="activity__cover"> <img src="img/cover/cover7.jpg" alt=""> </a>
                            <div class="activity__content">
                                <h3 class="activity__title"><a href="item.html">Elegance</a></h3>
                                <p class="activity__text">started following <a href="author.html">@johndoe</a></p>
                                <span class="activity__time">48 minutes ago</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6">
                        <div class="activity">
                            <a href="item.html" class="activity__cover"> <img src="img/cover/cover8.jpg" alt=""> </a>
                            <div class="activity__content">
                                <h3 class="activity__title"><a href="item.html">Walking on Air</a></h3>
                                <p class="activity__text">started following <a href="author.html">@johndoe</a></p>
                                <span class="activity__time">49 minutes ago</span>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="row row--grid">
                    <div class="col-12">
                        <button class="main__load" type="button" data-toggle="collapse" data-target="#collapsemore" aria-expanded="false" aria-controls="collapsemore">Load more</button>
                    </div>
                </div>
                <!-- end collapse -->
            </div>
            <!-- end content -->
        </div>         
    </div>
</main>
</template>
<script>
import mainHeader from "@/components/mainHeader.vue";
import mainFooter from "@/components/mainFooter.vue";

export default {
  name: "Activity",
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
