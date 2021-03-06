### Tooltips, Popovers and Modals

* Adding a Tooltip

  * In index.html we add a tooltip to the "Reserve Table"

  ```html
  <a role="button" class="btn btn-block nav-link btn-warning"
      data-toggle="tooltip" data-html="true"  title="Or Call us at  <br><strong>+852 12345678</strong>"
      data-placement="bottom" href="#reserveform">Reserve Table</a>
  ```

  * Now we add js function\(data-toggle="tooltip"\) to make action

  ```html
  <script>
      $(document).ready(function(){
      $('[data-toggle="tooltip"]').tooltip();
      });
  </script>
  ```

  * Demo

  ![](/assets/W3_3Tooltip.png)

* Adding a Modal

  * Create &lt;span&gt; on the right side of navbar to trigger the display of the modal \(\#loginModal\)

  ```
                  <span class="navbar-text">
                      <a data-toggle="modal" data-target="#loginModal">
                      <span class="fa fa-sign-in"></span> Login</a>
                  </span>
  ```

  * Set up the modal then that can get link and show on the webpage

  ```html
      <div id="loginModal" class="modal fade" role="dialog">
          <div class="modal-dialog modal-lg" role="content">
              <!-- Modal content-->
              <div class="modal-content">
                  <div class="modal-header">
                      <h4 class="modal-title">Login </h4>
                      <button type="button" class="close" data-dismiss="modal">&times;</button>
                  </div>
                  <div class="modal-body">
                      <form>
                          <div class="form-row">
                              <div class="form-group col-sm-4">
                                      <label class="sr-only" for="exampleInputEmail3">Email address</label>
                                      <input type="email" class="form-control form-control-sm mr-1" id="exampleInputEmail3" placeholder="Enter email">
                              </div>
                              <div class="form-group col-sm-4">
                                  <label class="sr-only" for="exampleInputPassword3">Password</label>
                                  <input type="password" class="form-control form-control-sm mr-1" id="exampleInputPassword3" placeholder="Password">
                              </div>
                              <div class="col-sm-auto">
                                  <div class="form-check">
                                      <input class="form-check-input" type="checkbox">
                                      <label class="form-check-label"> Remember me
                                      </label>
                                  </div>
                              </div>
                          </div>
                          <div class="form-row">
                              <button type="button" class="btn btn-secondary btn-sm ml-auto" data-dismiss="modal">Cancel</button>
                              <button type="submit" class="btn btn-primary btn-sm ml-1">Sign in</button>        
                          </div>
                      </form>
                  </div>
              </div>
          </div>
      </div>
  ```

* Demo

![](/assets/W3_3loginModal.png)

