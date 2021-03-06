# Accordion

* Converting Tabs to Accordion

  * delete &lt;ul&gt; class to replace card heading, and that &lt;p&gt; in the card body.

  ```html
                  <div id="accordion">
                      <div class="card">
                          <div class="card-header" role="tab" id="peterhead">
                              <h3 class="mb-0">
                                  <a data-toggle="collapse" data-target="#peter">
                                      Peter Pan <small>Chief Epicurious Officer</small>
                                  </a>
                              </h3>
                          </div>
                          <div class="collapse show" id="peter" data-parent="#accordion">
                              <div class="card-body">
                                  <p class="d-none d-sm-block">
                                      Our CEO, Peter, credits his hardworking East Asian immigrant parents who undertook
                                      the arduous journey to the shores of America with the intention of giving their
                                      children the best future. His mother's wizardy in the kitchen whipping up the
                                      tastiest dishes with whatever is available inexpensively at the supermarket, was
                                      his first inspiration to create the fusion cuisines for which <em>The Frying Pan</em>
                                      became well known. He brings his zeal for fusion cuisines to this restaurant,
                                      pioneering cross-cultural culinary connections.
                                  </p>
                              </div>
                          </div>
                      </div>
                      <div class="card">
                          <div class="card-header" role="tab" id="dannyhead">
                              <h3 class="mb-0">
                                  <a class="collapsed" data-toggle="collapse" data-target="#danny">
                                      Dhanasekaran Witherspoon <small>Chief Food Officer</small>
                                  </a>
                              </h3>
                          </div>
                          <div class="collapse" id="danny" data-parent="#accordion">
                              <div class="card-body">
                                  <p class="d-none d-sm-block">
                                      Our CFO, Danny, as he is affectionately referred to by his colleagues, comes from a
                                      long established family tradition in farming and produce. His experiences growing
                                      up on a farm in the Australian outback gave him great appreciation for varieties of
                                      food sources. As he puts it in his own words, <em>Everything that runs, wins, and
                                          everything that stays, pays!</em></em>
                                  </p>
                              </div>
                          </div>
                      </div>
                      <div class="card">
                          <div class="card-header" role="tab" id="agumbehead">
                              <h3 class="mb-0">
                                  <a class="collapsed" data-toggle="collapse" data-target="#agumbe">
                                      Agumbe Tang <small>Chief Taste Officer</small>
                                  </a>
                              </h3>
                          </div>
                          <div class="collapse" id="agumbe" data-parent="#accordion">
                              <div class="card-body">
                                  <p class="d-none d-sm-block">
                                      Blessed with the most discerning gustatory sense, Agumbe, our CFO, personally
                                      ensures that every dish that we serve meets his exacting tastes. Our chefs dread
                                      the tongue lashing that ensues if their dish does not meet his exacting standards.
                                      He lives by his motto, <em>You click only if you survive my lick.</em>
                                  </p>
                              </div>
                          </div>
                      </div>
                      <div class="card">
                          <div class="card-header" role="tab" id="albertohead">
                              <h3 class="mb-0">
                                  <a class="collapsed" data-toggle="collapse" data-target="#alberto">
                                      Alberto Somayya <small>Executive Chef</small>
                                  </a>
                              </h3>
                          </div>
                          <div class="collapse" id="alberto" data-parent="#accordion">
                              <div class="card-body">
                                  <p class="d-none d-sm-block">
                                      <p>Award winning three-star Michelin chef with wide International experience having
                                          worked closely with whos-who in the culinary world, he specializes in creating
                                          mouthwatering Indo-Italian fusion experiences. He says, <em>Put together the
                                              cuisines from the two craziest cultures, and you
                                              get a winning hit! Amma Mia!</em></p></em>
                                  </p>
                              </div>
                          </div>
                      </div>
  ```

  * Demo  
    ![](/assets/W3_2Accordion.png)



