<template>
    <div class="hero-container">
        <div class="custom-container">
            <div class="hero-content">
                <div class="hero-top">
                    <div class="hero-top-text">
                        <p>Capital raised</p>
                        <h1>$3.5M+</h1>
                        <p>
                            Crafted for your comfort, to enhance the beauty of
                            your present lifestyle but also paves the way for a
                            more aesthetically pleasing and harmonious future
                            for both you and your cherished family.
                        </p>
                    </div>

                    <h1>We craft the future dwelling.</h1>
                </div>

                <div class="hero-bottom">
                    <div class="left">
                        <div class="sub-hero"></div>
                    </div>
                    <div class="right">
                        <img src="../assets/Rectangle 750.png" alt="" />
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss">
.hero-container {
    padding: 45px 0;
    display: flex;
    justify-content: center;

    .hero-content {
        border-radius: 50px;
        padding-bottom: -30px;
        .hero-top {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            background-color: #f7f8f8;
            border-radius: 50px 50px 0px 50px;
            padding: 30px;

            .hero-top-text {
                width: 30%;
            }
        }

        .hero-bottom {
            border-radius: 0px;
            background-color: #f7f8f8;
            display: flex;
            border-radius: 50px 0px 50px 50px;

            .left {
                width: 40%;
                background: #fff;
                padding-top: 30px;
                padding-right: 30px;
                margin-bottom: -45px;
                border-radius: 0px 50px 0px 0px;

                .sub-hero {
                    width: 100%;
                    height: 100%;
                    background: #f7f8f8;
                    border-radius: 50px 50px 50px 50px;
                }
            }
            .right {
                width: 100%;
                display: flex;
                justify-content: center;
                align-items: center;
                background: #f7f8f8;
                border: solid 30px #f7f8f8;
                border-radius: 50px 50px 50px 50px;
                margin-bottom: -45px;

                img {
                    width: 100%;
                }
            }
        }
    }
}
</style>
