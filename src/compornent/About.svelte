<div class="container">
    <div class="row">
        <div class="col">
            <div class="serviceBox">
                <div class="service-icon">
                    <i class="fa fa-globe"></i>
                </div>
                <h3 class="title">Web Design</h3>
                <p class="description">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam cumque, cupiditate debitis dolorem et fugit hic iusto maxime numquam officia.
                </p>
            </div>
        </div>
        <div class="col">
            <div class="serviceBox">
                <div class="service-icon">
                    <i class="fa fa-briefcase"></i>
                </div>
                <h3 class="title">Web Development</h3>
                <p class="description">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam cumque, cupiditate debitis dolorem et fugit hic iusto maxime numquam officia.
                </p>
            </div>
        </div>
    </div>
</div>

<style>
    .col {
        margin-top: 120px;
    }
    .serviceBox{
        padding: 60px 45px 25px 10px;
        margin-top: 50px;
        background: #48392a;
        position: relative;
        transition: all 0.5s ease 0s
    }
    .serviceBox:hover{
        padding-left: 30px;
        padding-right: 20px;
        background: #f29e93;
    }
    .serviceBox .service-icon{
        width: 100px;
        height: 100px;
        line-height: 100px;
        border-radius: 10px;
        background: #48392a;
        font-size: 35px;
        color: #fbf2c0;
        text-align: center;
        position: absolute;
        top: -50px;
        left: 0;
        transition: all 0.5s ease 0s
    }
    .serviceBox:hover .service-icon{
        background: #f29e93;
        left: 30px;
    }
    .serviceBox .title{
        font-size: 20px;
        font-weight: 700;
        color: #fbf2c0;
        text-transform: uppercase;
        margin: 0 0 10px 0;
    }
    .serviceBox .description{
        font-size: 15px;
        color: #fbf2c0;
        line-height: 25px;
        margin: 0;
    }
    @media only screen and (max-width:990px){
        .serviceBox{ margin-bottom: 30px; }
    }
    @media only screen and (max-width:767px){
        .serviceBox{ margin-bottom: 70px; }
    }
    body input, button, textarea, select {
        -webkit-appearance: none;
        -moz-appearance: none;
        appearance: none;
    }
</style>
