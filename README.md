# 📦 Odoo Module Landing Page Template

A clean, responsive HTML landing page template to showcase Odoo modules — featuring screenshots, key highlights, and services section.

## 🌐 Live Demo

👉 [View Demo](https://aungmoewai1.github.io/module_info_template/)

## 🔧 Installation

1. Clone or download this repo.
2. Add or modify screenshots and highlight sections as needed.
3. Open `index.html` in a browser to preview.
4. Upload to your module's documentation or GitHub Page.


## 📁 Folder Structure

```text
├── index.html
├── assets/
│   ├── icons/
│   ├── screenshoots/
│   ├── feature_icons/
│   ├── odoo.png
│   └── SME Intellect Co., Ltd..png
```


---

## 🛠️ How to Use

### 1. 🖼️ Add Highlight Features

- Place your icons in the folder:  
  `assets/feature_icons/`

- Copy another one to add new highlight feature:

```html
<!--                Simple highlight part-->
                <div class="col-lg-4">
                    <div class="mb-4 d-flex flex-column justify-content-center gap-3"
                         style="border-radius: 12px; border: 1px solid  #B6BCCD; background:  #FFF;padding:32px ">
                        <div class="d-flex align-items-center" style="border-radius:8px !important; height:70px;">
<!--                            highlight Icon -->
                            <img src="./assets/feature_icons/simple_feature.png" class="img-responsive" height="40px"
                                 width="40px">
                            <h5 class="m-0 px-3" style="color:#000 !important; font-weight:bold">
                                Heading
                            </h5>
                        </div>
                        <p class="m-0" style="font-size: 16px; font-weight: 400; color:var(--text-color-light);">
                            paragraph description
                        </p>
                    </div>
                </div>

            </div>
        </div>
```


### 2. 🖼️ Add Custom Screenshots

- Place your screenshots in the folder:  
  `assets/screenshoots/`

- Replace the default image path in the HTML:

```html
<!--                                sub-heading can add here for each screenshoot-->
                                <div class="col-md-12">
                                    <p style="font-weight:400; font-size:16px; line-height:150%; color:var(--text-color-light);text-align:left;">
                                        Sub title or work flow description of image
                                    </p>
                                </div>
                                
<!--                                Screen shoot image can add by duplicate this div-->
                                <div class="col-md-12 text-center mb-3">
                                    <div class="d-inline-block p-3 shadow-sm"
                                         style="background-color:#fff; border-radius:10px">
                                        <!--                                        Here to change image-->
                                        <img alt="" class="img-fluid"
                                             loading="lazy"
                                             src="./assets/screenshoots/screenshoot.png"
                                             style="min-height: 1px;">
                                    </div>
                                </div>
```

---
### 👏 Contributions

Contributions and suggestions are welcome! Feel free to open issues or submit pull requests.

### 👨‍💻 Author

Developed by [SME Intellect Co., Ltd.](mailto:info@smeintellect.com)

