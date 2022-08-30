<template>
    <div class="row no-gutters flex align-items-end">
        <div class="col-2">
            <div class="row no-gutters align-items-end">
                <div class="col-2">
                    <div class="artists-slider">
                        <div id="media0" class="carousel slide" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media01" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media02" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media0" data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media0" data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
                <div class="col-10"></div>
                <div class="col-8">
                    <div class="artists-slider">
                        <div id="media2" class="carousel slide carousel-fade" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media02" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media01" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media2" data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media2" data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="artists-slider">
                        <div id="media3" class="carousel slide" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media02" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media01" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media3" data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media3" data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
                <div class="col-6">
                    <div class="artists-slider">
                        <div id="media4" class="carousel slide carousel-fade" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media02" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media01" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media4" data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media4" data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
                <div class="col-6">
                    <div class="artists-slider">
                        <div id="media5" class="carousel slide" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media02" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media01" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media5" data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media5" data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
                <div class="col-12">
                    <div class="artists-slider">
                        <div id="media6" class="carousel slide carousel-fade" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media02" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media01" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media6" data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media6" data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="col-3">
            <div class="row no-gutters align-items-end">
                <div class="col-3">
                    <div class="artists-slider">
                        <div id="media7" class="carousel slide" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media01" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media02" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media7" data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media7" data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
                <div class="col-2">
                    <div class="artists-slider">
                        <div id="media8" class="carousel slide carousel-fade" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media02" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media01" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media8" data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media8" data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
                <div class="col-7"></div>
                <div class="col-12">
                    <div class="artists-slider">
                        <div id="media9" class="carousel slide" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media02" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media01" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media9" data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media9" data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="col-3">
            <div class="row no-gutters align-items-end">
                <div class="col-7">
                    <div class="artists-slider">
                        <div id="media10" class="carousel slide carousel-fade" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media01" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media02" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media10"
                                data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media10"
                                data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
                <div class="col-5">
                    <div class="artists-slider">
                        <div id="media11" class="carousel slide" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media01" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media02" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media11"
                                data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media11"
                                data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
                <div class="col-6">
                    <div class="artists-slider">
                        <div id="media12" class="carousel slide" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media01" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media02" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media12"
                                data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media12"
                                data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
                <div class="col-6">
                    <div class="artists-slider">
                        <div id="media13" class="carousel slide carousel-fade" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media02" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media02" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media13"
                                data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media13"
                                data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="col-2">
            <div class="row no-gutters align-items-end">
                <div class="col-5">
                    <div class="artists-slider">
                        <div id="media14" class="carousel slide" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media01" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media14"
                                data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media14"
                                data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
                <div class="col-7">
                    <div class="artists-slider">
                        <div id="media15" class="carousel slide carousel-fade" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media01" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media15"
                                data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media15"
                                data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
                <div class="col-12">
                    <div class="artists-slider">
                        <div id="media16" class="carousel slide carousel-fade" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media01" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media16"
                                data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media16"
                                data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="col-2">
            <div class="row no-gutters align-items-end">
                <div class="col-2"></div>
                <div class="col-4">
                    <div class="artists-slider">
                        <div id="media17" class="carousel slide carousel-fade" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media01" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media17"
                                data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media17"
                                data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
                <div class="col-6">
                    <div class="artists-slider">
                        <div id="media18" class="carousel slide" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media02" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media01" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media18"
                                data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media18"
                                data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
                <div class="col-12">
                    <div class="artists-slider">
                        <div id="media19" class="carousel slide carousel-fade" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media02" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media01" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media19"
                                data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media19"
                                data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
                <div class="col-6">
                    <div class="artists-slider">
                        <div id="media20" class="carousel slide" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media01" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media20"
                                data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media20"
                                data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
                <div class="col-6">
                    <div class="artists-slider">
                        <div id="media21" class="carousel slide carousel-fade" data-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img :src="media02" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media01" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img :src="media03" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-target="#media21"
                                data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-target="#media21"
                                data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import media01 from "../assets/img/a0.jpg";
import media02 from "../assets/img/a1.jpg";
import media03 from "../assets/img/a4.jpg";
export default {
    setup() {

        return {
            media01,
            media02,
            media03,
        }
    }
}
</script>

<style>
</style>