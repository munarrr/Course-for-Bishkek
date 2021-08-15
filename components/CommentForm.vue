<template>
    <div class="comment-form" data-aos="fade-up" data-aos-duration="1000">
        <h2 class="title">Leav a <span>Reply</span></h2>
        <form>
            <div class="comment-form-content">
                <div class="row">
                    <div class="col-md-12">
                        <div class="form-group">
                            <input class="form-control" type="text" placeholder="Name" required="">
                        </div>
                    </div>
                    <div class="col-md-12">
                        <div class="form-group">
                            <input class="form-control" type="email" placeholder="Email Address" required="">
                        </div>
                    </div>
                    <div class="col-md-12">
                        <div class="form-group">
                            <textarea class="form-control textarea" name="comment" id="comment" cols="45" rows="7" placeholder="Message" required=""></textarea>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-12">
                        <div class="form-group group-style mb-0">
                            <button class="btn btn-theme" type="submit">Submit Now <i class="icon icofont-long-arrow-right"></i></button>
                        </div>
                    </div>
                </div>
            </div>
        </form>
    </div>
</template>

<script>
    export default {

    };
</script>
