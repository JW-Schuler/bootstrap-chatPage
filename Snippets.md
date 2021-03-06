# Präsentation Bootstrap 

#### Vorstellung:	
- Theorie 		--> URL zur Präsentation folgt ()
- Codetemplate 	--> Homepage einer Chat App mit Profil und Login

#### Relations: 
```html 
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" />
```

## NavBar:
```html 	 
<nav 
  	class="
    	navbar
    	navbar-expand-lg
    	navbar-light
    	bg-light
    	fixed-top"
  	><div  
    	class="container"
    	><a  
      		class="navbar-brand" 
      		href="./index.html"
      		>chatApp</a>
      	<button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
        ><span 
        class="navbar-toggler-icon"
        >></span>
        </button>
        <div 
          class="collapse
                navbar-collapse" 
          id="navbarSupportedContent"
          ><ul 
            class="navbar-nav
                  me-auto
                  mb-2
                  mb-lg-0"
            ><li
              class="nav-item"
            ><a 
              class="nav-link" 
              href="./login.html"
              >Login</a>
            </li>
            <li 
              class="nav-item"
              ><a 
                class="nav-link"
                href="./profile.html"
                >Profile</a>
            </li>
          </ul>
        </div>
    </div>
</nav>
```
## Chat frame
```html
<div 
    class=  "container
            pt-5"
    ><div
        class=  "row
                clearfix"
        ><div
            class="col-lg-12"
            ><div 
                class=  "card
                         chat-app"
                >
					Chat List Frame einfügen
					Chat einfügen
				</div>
            </div>
        </div>
    </div>
</div>
```
## Chat List Frame
```html
<div
      id="plist" 
      class="people-list"
      ><div 
          class="input-group"
          ><div 
              class="input-group-prepend"
              ><span 
                  class="input-group-text"
                  ><i 
                      class=  "fa
                               fa-search"
                  ></i>
              </span>
          </div>
          <input type="text" class="form-control" placeholder="Search...">
		  <ul 
    		class=  "list-unstyled
    		          chat-list
    		          mt-2
    		          mb-0"
    		  >
		  	Chat List einfügen
		  </ul>
      </div>
</div>
```
## Chat List
```html
<li 
          class="clearfix"
          ><img 
              src="./avatar.png" 
              alt="avatar"
          ><div 
              class="about"
              ><div 
                  class="name"
                  >Teresa Kahlenbach</div>
              <div 
                  class="status">
                  <i 
                      class=  "fa
                              fa-circle 
                              offline"
                      ></i> left 7 mins ago </div>
          </div>
      </li>
      <li 
          class="clearfix"
          ><img 
              src="./avatar.png" 
              alt="avatar"
              ><div 
                  class="about"
                  ><div 
                      class="name"
                      >Niklas Flaig</div>
                  <div 
                      class="status"
                      ><i 
                          class=  "fa
                                  fa-circle
                                  offline"
                          ></i> offline </div>
              </div>
      </li>
      <li 
      class="clearfix"
      ><img 
          src="./avatar.png" 
          alt="avatar"
          ><div 
              class="about"
              ><div 
                  class="name"
                  >Lisa Waeger</div>
              <div 
                  class="status"
                  ><i 
                      class=  "fa
                              fa-circle
                              offline"
                      ></i> offline </div>
          </div>
  </li>
  <li 
  class="clearfix"
  ><img 
      src="./avatar.png" 
      alt="avatar"
      ><div 
          class="about"
          ><div 
              class="name"
              >Enis Sentürk</div>
          <div 
              class="status"
              ><i 
                  class=  "fa
                          fa-circle
                          offline"
                  ></i> offline </div>
      </div>
  </li>
  <li 
  class="clearfix"
  ><img 
      src="./avatar.png" 
      alt="avatar"
      ><div 
          class="about"
          ><div 
              class="name"
              >Michael Kluge</div>
          <div 
              class="status"
              ><i 
                  class=  "fa
                          fa-circle
                          offline"
                  ></i> offline </div>
      </div>
  </li>
  <li 
  class="clearfix"
  ><img 
      src="./avatar.png" 
      alt="avatar"
      ><div 
          class="about"
          ><div 
              class="name"
              >Jannis Schuler</div>
          <div 
              class="status"
              ><i 
                  class=  "fa
                          fa-circle
                          online"
                  >
              </i> online </div>
      </div>
  </li>
```
## Chat mit Header 
```html
<div 
    class="chat"
    ><div
        class=  "chat-header
            clearfix"
        ><div 
            class="row"
            ><div 
                class="col-lg-6"
                ><a 
                    href="javascript:void(0);"
                    data-toggle="modal" 
                    data-target="#view_info"
                    >
                    <img 
                        src="./avatar.png" 
                        alt="avatar"
                        >
                </a>
                <div 
                    class="chat-about"
                    ><h6 
                        class="m-b-0"
                        >Niklas Flaig</h6>
                    <small>Last seen: 2 hours ago</small>
                </div>
            </div>
        </div>
    </div>
	Chat History einfügen
	Input einfügen
</div>

```
## Chat History 
```html
<div 
    class="chat-history"
    ><ul 
        class="m-b-0"
        >
		Chat List Items einfügen
	</ul>
</div>
```
## Chat List Item
```html
    <li 
        class="clearfix"
        ><div 
            class=  "message-data
                    text-right"
            ><span 
                class="message-data-time"
                >10:10 AM, Today</span>
            <img 
                src="./avatar.png" 
                alt="avatar"
                >
        </div>
        <div 
            class=  "message
                    other-message 
                    float-right"
            >Hi Niklas, wie geht's dir heute?</div>
    </li>
```
## Chat Input 
```html
<div 
    class=  "chat-message
            clearfix"
    ><div 
        class=  "input-group
                mb-0
                align-bottom"
        ><div 
            class="input-group-prepend"
            ><span 
                class="input-group-text"
                ><i 
                    class=  "fa
                            fa-send"
                    ></i>
            </span>
        </div>
        <input type="text" class="form-control" placeholder="Enter text here...">                                    
    </div>
</div>
```
## Login
```html
<div 
  class=" container 
        pt-5"
  ><div 
    class="row"
    ><div 
      class="col-md-8
            col-lg-8
            col-md-offset-4
            col-lg-offset-4"
      ><div 
        class="card"
        ><div 
          class="card-body"
          ><div 
            class="d-flex
                  flex-column
                  align-items-center
                  text-center"
              >
			  LoginForm und zusatz einfügen
			</div>
        </div>
      </div>
    </div> 
  </div>
</div>
```
## Login form
#### Headline einfügen nach belieben
```html
<form 
  role="form"
  class="ng-pristine
        ng-valid"
  ><div
    class="form-content"
    ><div 
      class="form-group
             p-2"
      ><input 
        type="text"
        class="form-control
               input-underline
               input-lg"
        placeholder="Email"
        >
    </div> 
    <div 
      class="form-group
             p-2"
      ><input 
        type="password" 
        class="form-control 
              input-underline 
              input-lg" 
        placeholder="Password"
        >
    </div> 
  </div> 
  <button 
    class="btn
          btn-info
          btn-lg"
    >Log in</button> &nbsp;
  <button
    type="submit"
    class="btn
          btn-info
          btn-lg"
    >Register</button>
</form> 
```
## Profil
#### Profil Frame
```html
<div 
    class=  "container
            pt-5"
    ><div 
        class="main-body"
        ><div 
            class=  "row
                    gutters-sm"
            >
			Erste Spalte einfügen
			Data Card einfügen
		</div>
	 </div>
  </div>
```
#### Erste Spalte
```html
<div 
    class=  "col-md-4
            mb-3"
    >
	User Card einfügen
    <div 
        class=  "card
                mt-3"
        ><ul 
            class=  "list-group
                    list-group-flush"
            >
			Social List Items einfügen
        </ul>
    </div>
</div>
```
#### User Card
```html
<div 
    class="card"
    ><div 
        class="card-body"
        ><div 
            class=  "d-flex 
                    flex-column
                    align-items-center
                    text-center"
                    ><img 
                        src="avatar.png" 
                        alt="Admin"
                        class="rounded-circle"
                        width="150"
                    ><div 
                    class="mt-3"
                    ><h4>Jannis Schuler</h4>
                    <p 
                        class=  "text-secondary
                                mb-1"
                        >Design Student</p>
                    <p 
                        class=  "text-muted
                                font-size-sm"
                        >73525 Schwäbisch Gmünd, Schindelackerweg 45</p>
                    <button 
                        class=  "btn
                                btn-primary"
                        >Follow</button>
                    <button 
                        class=  "btn
                                btn-outline-primary"
                        >Message</button>
                    </div>
        </div>
    </div>
</div>
```
#### Social List Items
```html
<li 
    class=  "list-group-item
            d-flex
            justify-content-between
            align-items-center
            flex-wrap"
    ><h6 
        class="mb-0"
        ><svg 
            xmlns="http://www.w3.org/2000/svg" 
            width="24" 
            height="24" 
            viewBox="0 0 24 24" 
            fill="none" s
            troke="currentColor" 
            stroke-width="2" 
            stroke-linecap="round" 
            stroke-linejoin="round" 
            class=  "feather 
                    feather-globe
                    mr-2
                    icon-inline"
                    ><circle 
                        cx="12"
                        cy="12"
                        r="10"
                        ></circle>
                    <line 
                        x1="2"
                        y1="12"
                        x2="22"
                        y2="12"
                        ></line>
                    <path 
                        d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"
                        ></path>
        </svg>
    Website</h6>
    <span 
        class="text-secondary"
        >ersetzen</span>
</li>
<li 
    class=  "list-group-item
            d-flex
            justify-content-between
            align-items-center
            flex-wrap"
    ><h6 
        class="mb-0"
        ><svg 
            xmlns="http://www.w3.org/2000/svg" 
            width="24" 
            height="24" 
            viewBox="0 0 24 24" 
            fill="none" 
            stroke="currentColor" 
            stroke-width="2" 
            stroke-linecap="round" 
            stroke-linejoin="round" 
            class=  "feather
                    feather-github
                    mr-2
                    icon-inline"
            ><path 
                d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"
                ></path>
        </svg>
    Github</h6>
    <span class="text-secondary">ersetzen</span>
</li>
<li 
    class=  "list-group-item
            d-flex
            justify-content-between
            align-items-center
            flex-wrap"
    ><h6 
        class="mb-0"
        ><svg 
            xmlns="http://www.w3.org/2000/svg" 
            width="24" 
            height="24" 
            viewBox="0 0 24 24" 
            fill="none" 
            stroke="currentColor" 
            stroke-width="2" 
            stroke-linecap="round" 
            stroke-linejoin="round" 
            class=  "feather
                    feather-twitter
                    mr-2
                    icon-inline
                    text-info"
            ><path 
                d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z"
                ></path>
        </svg>
    Twitter</h6>
    <span class="text-secondary">ersetzen</span>
</li>
<li 
    class=  "list-group-item 
            d-flex 
            justify-content-between 
            align-items-center 
            flex-wrap"
    ><h6 
        class="mb-0"
        ><svg 
            xmlns="http://www.w3.org/2000/svg" 
            width="24" 
            height="24" 
            viewBox="0 0 24 24" 
            fill="none" 
            stroke="currentColor" 
            stroke-width="2" 
            stroke-linecap="round" 
            stroke-linejoin="round" 
            class=  "feather
                    feather-instagram
                    mr-2
                    icon-inline
                    text-danger"
            ><rect 
                x="2"
                y="2" 
                width="20" 
                height="20" 
                rx="5" 
                ry="5"
                ></rect>
            <path 
                d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"
                ></path>
            <line 
                x1="17.5" 
                y1="6.5" 
                x2="17.51" 
                y2="6.5"
                ></line>
        </svg>
    Instagram</h6>
    <span class="text-secondary">ersetzen</span>
</li>
<li 
    class=  "list-group-item
            d-flex 
            justify-content-between 
            align-items-center 
            flex-wrap"
    ><h6 
        class="mb-0"
        ><svg 
            xmlns="http://www.w3.org/2000/svg" 
            width="24" 
            height="24" 
            viewBox="0 0 24 24" 
            fill="none" 
            stroke="currentColor" 
            stroke-width="2" 
            stroke-linecap="round" 
            stroke-linejoin="round" 
            class=  "feather 
                    feather-facebook 
                    mr-2 
                    icon-inline 
                    text-primary"
            ><path 
                d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"
                ></path>
        </svg>
    Facebook</h6>
    <span class="text-secondary">ersetzen</span>
</li>
``` 
#### Data Card
```html
<div 
    class="col-md-8"
    ><div 
        class="card mb-3"
        ><div 
            class="card-body"
            ><div 
                class="row"
                ><div 
                    class="col-sm-3"
                    ><h6 
                        class="mb-0"
                        >
                    Name</h6>
                </div>
                <div 
                    class=  "col-sm-9
                            text-secondary"
                    >
                Jannis Schuler</div>
            </div>
            <hr>
            <div 
                class="row"
                ><div 
                    class="col-sm-3"
                    ><h6 
                        class="mb-0"
                        >
                    Email</h6>
                </div>
                <div 
                    class=  "col-sm-9
                            text-secondary"
                    >
                jannis.schuler@hfg.design</div>
            </div>
            <hr>
            <div 
                class="row"
                ><div 
                    class="col-sm-3"
                    ><h6 
                        class="mb-0"
                        >
                    Mobile</h6>
                </div>
                <div 
                    class=  "col-sm-9
                            text-secondary"
                    >
                +4915231946067</div>
            </div>
            <hr>
            <div 
                class="row"
                ><div 
                    class="col-sm-3"
                    ><h6 
                        class="mb-0"
                        >
                    Address</h6>
                </div>
                <div 
                    class=  "col-sm-9
                             text-secondary"
                    >
                73525 Schwäbisch Gmünd, Schindelackerweg 45</div>
            </div>
            <hr>
            <div 
                class="row"
                ><div 
                    class="col-sm-12"
                    ><a class=  "btn
                                 btn-info" 
                        target="__blank" 
                        href="#"
                        >
                    Edit</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
```
