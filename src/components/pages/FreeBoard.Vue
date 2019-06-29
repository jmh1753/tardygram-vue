<template>
    <div>    
        <!-- <컴포넌트></컴포넌트> -->
        <headerComponent></headerComponent>
    
        <!-- inner-banner -->
        <section class="inner-banner" id="home">
            <div class="inner-layer">
                <div class="container">
                </div>
            </div>
        </section>
        <!-- //inner-banner -->

        <!-- breadcrumb -->
        <div class="breadcrumb-w3pvt">
            <div class="container">
            <nav aria-label="breadcrumb">
                <ol class="breadcrumb">
                    <li class="breadcrumb-item">
                        <a href="index.html">Home</a>
                    </li>
                    <li class="breadcrumb-item" aria-current="page">Freeboard</li>
                </ol>
            </nav>
            </div>
        </div>
        <!-- //breadcrumb -->

        <div class="container">
            <table class="table">
                <thead>
                    <tr>
                        <th style="width:10%">no</th>
                        <th style="width:50%">제목</th>
                        <th style="width:15%">글쓴이</th>
                        <th style="width:15%">작성일</th>
                        <th style="width:10%">조회수</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <th>4</th>
                        <td>test</td>
                        <td>test</td>
                        <td>19/06/29</td>
                        <td>100</td>
                    </tr>
                    <tr>
                        <th>3</th>
                        <td><router-link to="/freeboarddetail">처음으로 가입했어요 반가워요</router-link></td>
                        <td>문호</td>
                        <td>19/06/29</td>
                        <td>100</td>
                    </tr>
                    <tr>
                        <th>2</th>
                        <td>저도 처음이에요</td>
                        <td>형우</td>
                        <td>19/06/29</td>
                        <td>100</td>
                    </tr>
                    <tr>
                        <th>1</th>
                        <td>저도 처음이에요</td>
                        <td>길하</td>
                        <td>19/06/29</td>
                        <td>100</td>
                    </tr>
                </tbody>
            </table>
            <router-link class="btn btn-outline-secondary btn-sm" to="/insertfreeboard">글쓰기</router-link>
            

        </div>


        
        <br><br><br><br><br><br><br><br><br>
        <copyright></copyright>      
        <movetop></movetop>
    </div>
</template>

<script>
import headerComponent from "../common/HeaderComponent"
import copyright from "../common/copyright"
import movetop from "../common/movetop"
export default {
    data(){
        return{

        }
    },
    components:{
        headerComponent,
        copyright,
        movetop
    },
    methods:{
        
    }
}
</script>



<style scoped>



</style>
