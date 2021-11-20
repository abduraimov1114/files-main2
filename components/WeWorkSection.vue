<template>
  <div>

    <section class="we-work-section">
      <div class="auto-container">
        <div class="sec-title centered">
          <h2>We Work With industries <span class="dot">.</span></h2>
        </div>
        <!--Work Tabs-->
        <div class="work-tabs tabs-box">

          <!--Tabs Container-->
          <div class="tabs-content">

            <div class="tabs">

              <!--Tab-->
              <input type="radio" name="tabs" id="tabone" checked="checked">
              <label for="tabone" class="tab-btn">Latest technology</label>
              <div class="tab">
                <div class="tab active-tab">
                  <div class="row clearfix">
                    <div class="image-col col-lg-5 col-md-6 col-sm-12">
                      <div class="inner">
                        <div class="image">
                          <img src="/images/resource/featured-image-14.jpg" alt="">
                        </div>
                      </div>
                    </div>
                    <div class="text-col col-lg-7 col-md-6 col-sm-12">
                      <div class="inner">
                        <div class="content">
                          <div class="text">
                            <p>There are many variations of passages of lorem ipsum available, but
                              the majority have suffered alteration in some form, by injected
                              humour, or randomised words which don't look even slightly
                              believable.</p>
                            <p class="theme_color">If you are going to use a passage of Lorem Ipsum,
                              you need to be sure there isn't anything embarrassing hidden in the
                              middle of text. </p>
                            <ul>
                              <li>Self-contained, state-of-the-art time clock</li>
                              <li>Scalability of up to 500 employees per time clock</li>
                              <li>The ability to connect up to 32 time clocks</li>
                              <li>Employee self-enrollment</li>
                            </ul>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <!--Tab-->
              <input type="radio" name="tabs" id="tabtwo">
              <label for="tabtwo" class="tab-btn">awesome support</label>
              <div class="tab">
                <div class="tab active-tab">
                  <div class="row clearfix">
                    <div class="image-col col-lg-5 col-md-6 col-sm-12">
                      <div class="inner">
                        <div class="image">
                          <img src="/images/resource/featured-image-14.jpg" alt="">
                        </div>
                      </div>
                    </div>
                    <div class="text-col col-lg-7 col-md-6 col-sm-12">
                      <div class="inner">
                        <div class="content">
                          <div class="text">
                            <p>There are many variations of passages of lorem ipsum available, but
                              the majority have suffered alteration in some form, by injected
                              humour, or randomised words which don't look even slightly
                              believable.</p>
                            <p class="theme_color">If you are going to use a passage of Lorem Ipsum,
                              you need to be sure there isn't anything embarrassing hidden in the
                              middle of text. </p>
                            <ul>
                              <li>Self-contained, state-of-the-art time clock</li>
                              <li>Scalability of up to 500 employees per time clock</li>
                              <li>The ability to connect up to 32 time clocks</li>
                              <li>Employee self-enrollment</li>
                            </ul>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <!--Tab-->
              <input type="radio" name="tabs" id="tabthree">
              <label for="tabthree" class="tab-btn">1 click demo install</label>
              <div class="tab">
                <div class="tab active-tab">
                  <div class="row clearfix">
                    <div class="image-col col-lg-5 col-md-6 col-sm-12">
                      <div class="inner">
                        <div class="image">
                          <img src="/images/resource/featured-image-14.jpg" alt="">
                        </div>
                      </div>
                    </div>
                    <div class="text-col col-lg-7 col-md-6 col-sm-12">
                      <div class="inner">
                        <div class="content">
                          <div class="text">
                            <p>There are many variations of passages of lorem ipsum available, but
                              the majority have suffered alteration in some form, by injected
                              humour, or randomised words which don't look even slightly
                              believable.</p>
                            <p class="theme_color">If you are going to use a passage of Lorem Ipsum,
                              you need to be sure there isn't anything embarrassing hidden in the
                              middle of text. </p>
                            <ul>
                              <li>Self-contained, state-of-the-art time clock</li>
                              <li>Scalability of up to 500 employees per time clock</li>
                              <li>The ability to connect up to 32 time clocks</li>
                              <li>Employee self-enrollment</li>
                            </ul>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

          </div>
        </div>
      </div>
    </section>

  </div>
</template>

<script>
    export default {
      name: "WeWorkSection",
    }
</script>

<style>

  .tabs {
    display: flex;
    flex-wrap: wrap;
  }
  .tabs label {
    order: 1;
    display: block;
    padding: 20px 105px;
    margin-right: 0.2rem;
    cursor: pointer;
    background: #FFAA17;
    font-weight: bold;
    transition: background ease 0.2s;
    font-size: 22px;
    text-transform: uppercase;
    color: #222;
  }
  .tabs .tab {
    order: 99;
    flex-grow: 1;
    width: 100%;
    display: none;
    padding: 1rem;
    background: #F4F5F8;
  }
  .tabs input[type="radio"] {
    display: none;
  }
  .tabs input[type="radio"]:checked + label {
    background: #F4F5F8;
  }
  .tabs input[type="radio"]:checked + label + .tab {
    display: block;
  }

  @media (max-width: 45em) {
    .tabs .tab,
    .tabs label {
      order: initial;
    }
    .tabs label {
      width: 100%;
      margin-right: 0;
      margin-top: 0.2rem;
    }
  }

</style>
