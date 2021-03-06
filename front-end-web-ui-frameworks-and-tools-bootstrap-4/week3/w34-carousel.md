### Carousel

* Adding a Carousel

  * add basic carousel and add content inside the carousel

  ```html
                  <div id="mycarousel" class="carousel slide" data-ride="carousel">
                      <div class="carousel-inner" role="listbox">
                          <div class="carousel-item active">
                              <img class="d-block img-fluid" src="img/uthappizza.png" alt="Uthappizza">
                              <div class="carousel-caption d-none d-md-block">
                                  <!-- <h2>Uthappizza <span class="badge badge-danger">HOT</span> <span class="badge badge-pill badge-default">$4.99</span></h2> -->
                                  <h2 class="media-heading">Uthappizza <span class="label label-danger">Hot</span> <span
                                          class="badge">$4.99</span></h2>
                                  <p>A unique combination of Indian Uthappam (pancake) and
                                      Italian pizza, topped with Cerignola olives, ripe vine
                                      cherry tomatoes, Vidalia onion, Guntur chillies and
                                      Buffalo Paneer.</p>
                                  <p><a class="btn btn-primary btn-xs" href="#">More &raquo;</a></p>
                              </div>
                          </div>
                          <div class="carousel-item">
                              <img class="d-block img-fluid" src="img/buffet.png" alt="Buffet">
                              <div class="carousel-caption d-none d-md-block">
                                  <h2>Weekend Grand Buffet <span class="label label-danger">New</span></h2>
                                  <p>Featuring mouthwatering combinations with a choice of five different salads, six
                                      enticing appetizers, six main entrees and five choicest desserts. Free flowing
                                      bubbly and soft drinks. All for just $19.99 per person </p>
                                  <p><a class="btn btn-primary btn-xs" href="#">More &raquo;</a></p>
                              </div>

                          </div>
                          <div class="carousel-item">
                              <img class="d-block img-fluid" src="img/alberto.png" alt="Alberto Somayya">
                              <div class="carousel-caption d-none d-md-block">
                                  <h2 class="media-heading">Alberto Somayya</h2>
                                  <h4>Executive Chef</h4>
                                  <p>Award winning three-star Michelin chef with wide International experience having
                                      worked closely with whos-who in the culinary world, he specializes in creating
                                      mouthwatering Indo-Italian fusion experiences.</p>
                                  <p><a class="btn btn-primary btn-xs" href="#">More &raquo;</a></p>
                              </div>
                          </div>
                          <ol class="carousel-indicators">
                              <li data-target="#mycarousel" data-slide-to="0" class="active"></li>
                              <li data-target="#mycarousel" data-slide-to="1"></li>
                              <li data-target="#mycarousel" data-slide-to="2"></li>
                          </ol>
                          <a class="carousel-control-prev" href="#mycarousel" role="button" data-slide="prev">
                              <span class="carousel-control-prev-icon"></span>
                          </a>
                          <a class="carousel-control-next" href="#mycarousel" role="button" data-slide="next">
                              <span class="carousel-control-next-icon"></span>
                          </a>
                      </div>
                  </div>
  ```

* Add Css classes

```css
.carousel {
    background:#512DA8;
}

.carousel-item {
  height: 300px;
}

.carousel-item img {
    position: absolute;
    top: 0;
    left: 0;
    min-height: 300px;
}
```

* Add Carousel Controls

```html
<ol class="carousel-indicators">
    <li data-target="#mycarousel" data-slide-to="0" class="active"></li>
    <li data-target="#mycarousel" data-slide-to="1"></li>
    <li data-target="#mycarousel" data-slide-to="2"></li>
</ol>
<a class="carousel-control-prev" href="#mycarousel" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon"></span>
</a>
<a class="carousel-control-next" href="#mycarousel" role="button" data-slide="next">
    <span class="carousel-control-next-icon"></span>
</a>
```

* Demo

![](/assets/W3_4Carousel.png)



