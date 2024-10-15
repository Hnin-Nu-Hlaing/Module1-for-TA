# ✨ (1-1)

- ဒီသင်ခန်းစာမှာ HTML code ရဲ့ ပထမတစ်ဆင့်ဖြစ်တဲ့ အရေးကြီးတဲ့ Tools နဲ့ Processes တွေအကြောင်းသင်ကြားပေးမှာဖြစ်ပါတယ်

## 💡 ရေးသားရမည့် ပုံစံ
 ![Webpage titled "(1-1)example" features "Run Buddy" heading, a spot for an "what we do", "what you do", "meet the trainwers " and "reach out" section.](./image/(1-1)example.png)

## ရေးပုံရေးသားနည်း

### comment ရေးနည်း
- ရေးသားထားတဲ့codeများကို လွယ်လွယ်ကူကူ ဖတ်နိုင်ပြီး နားလည်စေဖို့ ပထမဆုံး comment ကိုထည့်ရေးပေးရမည်။ 

- (ctrl + /) ကိုအသုံးပြု၍ ရေးသားရမည်။

-![comment syntax](./image/comment-example.png)

### HTML code ရေးနည်း
-  ဒီသင်ခန်းစာရဲ့ body tag ထဲမှာဆိုရင်တော့ HTML တစ်ခုတည်းဖြင့်သာ သီးသန့်အသုံးပြု သင်ကြားပေးထားပါသည်။

- (1-1) ရဲ့ body မှာဆိုရင်တော့ အပိုင်းတစ်ခုခြင်းစီအတွက် section tagsကိုအသုံးပြုထားပါတယ်။

- Section tags 5ခုဖြင့် ရေးထားပြီး (1st section - "Hero/Jumbotron" section, 2nd section - "what we do" section, 3rd section - "what you do" section, 4th section - "meet the trainers" section, 5th section - "Reach Out" section) တို့ဖြစ်ပါတယ်။

- Section တစ်ခုချင်းစီရဲ့ title အတွက် "h2" tag ကိုအသုံးပြုပေးရမယ်။ Header ပိုင်းတွင် "h1" tag ကိုအသုံးပြူထားခြင်းကြောင့် body ပိုင်းဧ။် section တစ်ခုချင်းစီတွင် "h2" tagကိုအသုံးပြုပေးရခြင်းဖြစ်ပါသည်။

        <!-- hero/ jumbotron -->
        <section>
        </section>

        <!-- "what we do" section -->
        <section>
          <h2>What We Do</h2>
        </section>

        <!-- "what you do" section -->
        <section>
          <h2>What You Do</h2>
        </section>

        <!-- "meet the trainers" section -->
        <section>
          <h2>Meet The Trainers</h2>
        </section>

        <!-- "reach out" section -->
        <section>
          <h2>Reach Out</h2>
        </section>

# ✨ (1-2)

- Lesson(1-1)မှာဆိုရင် HTML သီးသန့်သာ သုံးထားပြီး lesson(1-2)မှာဆိုရင်တော့ CSSကို စတင်အသုံးပြုလာပြီး HTML နဲ့ CSS ကိုဘယ်လိုချိတ်ဆက် အသုံးပြုရမလဲဆိုတာ သင်ကြားပေးထားပါတယ်။

## 💡 CSS Syntax (css ရေးသားနည်း)

- CSS ရေးသားနည်း အမျိုးမျိုးရှိပြီး အသုံးပြုသူ(user)တွေက (property)လို့ခေါ်တဲ့ ကြိုတင်သတ်မှတ်ပြီးသား designပြုပြင်နိုင်သော (style characteristic)ကို HTML element (HTML tags) များနှင့်တွဲပြီး အသုံးပြုနိုင်ပါတယ်။

- အောက်ပါပုံတွင်ပြထားသည့်အတိုင်း CSS syntax အချို့ကို ကြည့်နိုင်ပါတယ်

![css syntax](./image/css-syntax.png)

### ရှင်းပြချက်

#### Selector
- Selector ဆိုတာ HTML element လို့ခေါ်တဲ့ (body tag)ကို ခေါ်သုံးထားခြင်းဖြစ်ပြီး element selectorလို့ခေါ်ခြင်းဖြစ်ပါတယ်။
 
- (class)ကိုခေါ်သုံးရင် class selector လို့ခေါ်ပြီး (id)ကိုခေါ်သုံးရင် id selector လို့ခေါ်ပါတယ်။

#### Property name
- Selectorကိုခေါ်ပြီးနောက် {} (curly brackets)ကိုခေါ်ပြီး {} (curly brackets) ထဲတွင် အသုံးပြုချင်သော property name ကိုခေါ်ပြီး အသုံးပြုနိုင်ပါတယ်။

- CSS properties name ရဲ့ examples တွေကတော့ color(စာသားအရောင်), background-image (နောက်ခံပုံထည့်ခြင်း), font-family (စာသားပုံစံပြောင်းခြင်း) အစရှိသဖြင့် အမျိုးမျိုးရှိကြပါတယ်။

#### Property value

- Property value ဆိုတာ property name ကိုအထူးပြုထားခြင်းကိုဆိုလိုပါတယ်။

- CSS properties value ရဲ့ examples တွေကတော့ (color:red;)ထဲမှာဆိုရင်တော့ red ကိုကိုယ်စားပြုခြင်းဖြစ်ပါတယ်။

#### Declaration terminator

- Declaration terminator ဆိုတာ property တစ်ခုနဲ့တစ်ခုကို အဆုံးတွင် ချိတ်ဆက်ပေးသော semicolon (;)ကို ခေါ်ခြင်းဖြစ်ပါတယ်။

- semicolon (;) မပါရင် propertiesတွေက အလုပ်မလုပ်သောကြောင့် semicolon (;)ကိုမဖြစ်မနေ ရေးပေးရပါမည်။

## 💡 ရေးသားရမည့် ပုံစံ 
 ![Webpage titled "(1-2)example" features "Run Buddy" heading, a spot for an "what we do", "what you do", "meet the trainers " and "reach out" section.](./image/(1-2)example.png)

## ရေးပုံရေးသားနည်း

### HTML နှင့် CSS ချိတ်ဆက်နည်း

- "html tag" ရဲ့ head ထဲမှာ "link tag" ကိုခေါ်သုံးရမည်။
        
        <link rel="stylesheet" href="">

- link tagထဲရှိ href (Hyper Reference)ထဲတွင် file ဧ။်တည်နေရာကိုရွေးပြီး ချိတ်ဆက်ပေးရမည်။


        <link rel="stylesheet" href="./assets/css/style.css" />


### CSS code ရေးနည်း

- ဒီသင်ခန်းစာမှာ css properties ကိုသုံးပြီးတော့ color ဘယ်လို change လဲဆိုတာ ပြောပြပေးထားပါတယ်။

- Bodyပိုင်းမှာဆိုရင်တော့ CSSကိုသုံးပြီး text colorကိုပြောင်းထားပါတယ်။

        body {
          color: #39a6b2;
          font-family: Helvetica, Arial, sans-serif;
        }

# ✨(1-3)

- (1-3)ရဲ့ bodyပိုင်းမှာဆိုရင်တော့ (Hero/Jumbotron) Bckground Image ထည့်ပြီး (Sign-Up Form) နာမည်စာရင်းပေးနည်းပုံစံ ရေးသားနည်းကို သင်ကြားပေးထားပါသည်။

## 💡 ရေးသားရမည့် ပုံစံ 
![Webpage titled "(1-3)example" features "Run Buddy" heading, a spot for an "Hero/Jumbotron" section.](./image/(1-3)example.png)

## ရေးပုံရေးသားနည်း

### Hero structure (Background Image) တည်ဆောက်နည်း

![](./image/hero-bg.jpg)

- html elementတစ်ခုကို အသုံးပြုပြီး Hero Section တစ်ခု တည်​ဆောက်ရပါမယ်။

- Hero section ကိုအထူးပြုတဲ့ class attribute ကို  section tagထဲတွင် ထည့်ရေးပေးရပါမယ်။

- Hero section ထဲတွင် sign-up-form ပေါ်ချင်သောကြောင့် html element (tag) တစ်ခု တည်ဆောက်ပေးရမည်။

- sign-up-formကိုအထူးပြုတဲ့ class attribute ကို  တည်ဆောက်ထားသော element ထဲတွင် ထည့်ရေးပေးရပါမယ်။

- Hero section အတွင်း၌ image ပေါ်ချင်သောကြောင့် css positionကို  relative ထည့်ရေးပြီး sign-up formကို image ပေါ်တွင်ပေါ်ချင်သောကြောင့် css positionကို  absolute ထည့်ရေးပေးရမည်။


#### HTML code ရေးနည်း
      <!-- hero/jumbotron -->
      <section class="hero">
        <div class="hero-form">
          
        </div>
      </section>  


#### CSS code ရေးသားနည်း
        .hero {
                background-image: url('../images/hero-bg.jpg');
                height: 600px;
                background-size: cover;
                background-position: center;
                position: relative;
              }

### Sign-Up Form ထည့်နည်း

- Background image တွက်သူံးထားသော section tagထဲတွင် sign-up form ကိုရေးရမည်။
- Section tag အတွင်းရှိသော divထဲတွင် form tag

#### ထည့်ရမည့်ပုံစံ

![](./image/sign%20-up.png)

#### Html code ရေးနည်း

        <!-- hero/jumbotron -->
        <section class="hero">
          <div class="hero-form">
            <h3>Get Started Today</h3>
            <p>Fill out this form and one of our trainers will schedule a consult</p>
            <form>
              <label for="name">Enter full name:</label>
              <input type="text" placeholder="Your Name" name="name" id="name" class="form-input" />
              <label for="email">Enter email address:</label>
              <input type="text" placeholder="Email Address" name="email" id="email" class="form-input" />
              <label for="phone">Enter a telephone number:</label>
              <input type="text" placeholder="Phone Number" name="phone" id="phone" class="form-input" />
              <p>
                Have you worked out with a trainer before?
                <input type="radio" name="trainer-confirm" id="trainer-yes" />
                <label for="trainer-yes">Yes</label>
                <input type="radio" name="trainer-confirm" id="trainer-no" />
                <label for="trainer-no">No</label>
              </p>
              <p>
                <label for="checkbox">
                  I acknowledge that I am at least 18 years of age.
                </label>
                <input type="checkbox" name="checkpoint1" id="checkbox" />
              </p>
              <button type="submit">
                Get running!
              </button>
            </form>
          </div>
        </section>

#### CSS code ရေးနည်း

        .hero-form {
          border: 3px solid #024e76;
          background-color: #fce138;
          padding: 20px;
          width: 500px;
          color: #024e76;
          position: absolute;
          bottom: 120px;
          right: 140px;
        }

        .hero-form h3 {
          font-size: 24px;
          margin: 0;
        }
        .hero-form p {
          margin: 5px 0 15px 0;
        }

        .form-input {
          border: 1px solid #024e76;
          display: block;
          padding: 7px 15px;
          font-size: 16px;
          color: #024e76;
          width: 100%;
          margin-bottom: 15px;
        }

        .hero-form label {
          margin: 0 5px;
        }

        .hero-form button {
          color: #fce138;
          background-color: #024e76;
          border: none;
          padding: 10px 20px;
          font-size: 16px;
        }

# ✨(1-4)        

- (1-4) အပိုင်းမှာ What we do and What you do section ရေးသားနည်းကြောင်း ဖော်ပြပေးမှာဖြစ်ပါတယ်

## 💡ရေးရမည့် ပုံစံမှာ

![What we do and what you do section](./image/(1-4)example.png)

#### What we do section ရေးသားနည်း

- What we do section ထဲတွင် h2 and p tags နှစ်ခုထဲသာ အသုံးပြုထားပြီး CSS အသုံးပြုထားပါသည်။

#### Html ရေးသားနည်း 

      <!-- "what we do" section -->
      <section id="what-we-do" class="intro">
        <h2 class="section-title primary-border">What We Do</h2>
        <p>
          butcher selfies chambray shabby chic gentrify readymade yr Echo Park XOXO Tumblr normcore Banksy direct trade Blue
          Bottle chillwave you probably haven't heard of them single-origin coffee Vice fanny pack fixie Odd Future Austin
          fingerstache pickled twee synth Wes Anderson Thundercats viral bitters flannel meggings narwhal Marfa Schlitz
          sustainable Intelligentsia umami deep v craft
        </p>
      </section>

#### CSS ရေးနည်း

      .intro {
        text-align: center;
      }
      .intro p {
        line-height: 1.7;
        color: #39a6b2;
        width: 80%;
        font-size: 20px;
        margin: 0 auto;
      }
      (section နှစ်ခုလုံး)
      .section-title {
        font-size: 55px;
        color: #024e76;
        margin-bottom: 35px;
        padding: 0 100px 20px 100px;
        display: inline-block;
        border-bottom: 3px solid;
      }

      .primary-border {
        border-color: #fce138;
      }

#### What we do section ရေးသားနည်း

- What we do section ထဲတွင် photoလေးပုံပါလာပြီး ထိုphoto များကို img tag နဲ့ ရေးပါသည်, h3 and p tags များပါဝင်ပါသည်။

#### HTML Code ရေးနည်း

    <!-- "what you do" section -->
      <section id="what-you-do" class="steps">
        <h2 class="section-title secondary-border">What You Do</h2>

        <div>
          <img src="./assets/images/step-1.svg" alt="" />
          <h3>Step 1: <span>Fill Out the Form Above.</span></h3>
          <p>You're already here, so why not?</p>
        </div>

        <div>
          <img src="./assets/images/step-2.svg" alt="" />
          <h3>Step 2: <span>Consult with One of Our Trainers.</span></h3>
          <p>Are you here to build muscle, lose weight, or just feel good?</p>
        </div>

        <div>
          <img src="./assets/images/step-3.svg" alt="" />
          <h3>Step 3: <span>Get Running.</span></h3>
          <p>Hit the ground running (literally) once your trainer lays out your plan.</p>
        </div>

        <div>
          <img src="./assets/images/step-4.svg" alt="" />
          <h3>Step 4: <span>See Results.</span></h3>
          <p>Bi-weekly checkins with your trainer will keep you focused</p>
        </div>
      </section>

#### CSS Code ရေးနည်း

.secondary-border {
  border-color: #39a6b2;
}
.steps {
  text-align: center;
  background: #fce138;
}

.steps div {
  margin-bottom: 80px;
}

.steps img {
  width: 15%;
  margin: 10px 0;
}

.steps h3 {
  color: #024e76;
  font-size: 46px;
  margin-top: 10px;
}

.steps p {
  color: #39a6b2;
  font-size: 23px;
}

.steps span {
  font-size: 38px;
}

# ✨(1-5)

- (1-5) အပိုင်းမှာ meet the trainer section အပိုင်း ရေးသားမှာဖြစ်ပါတယ်။
- meet the trainer section အပိုင်းတွင် trainer သုံးယောက်ပါဝင်ပါသည်။

## 💡ရေးမည့်ပုံစံ

![meet the trainer](./image/(1-5)example.png)

#### HTML Code ရေးနည်း

        <!-- "meet the trainers" section -->
          <section id="your-trainers" class="trainers">
            <h2 class="section-title primary-border">Meet The Trainers</h2>
            <article class="trainer">
              <img src="./assets/images/trainer-1.jpg" alt="Arron Stephens in his workout clothes, ready to pump iron" />
              <div class="trainer-bio text-left">
                <h3>Arron Stephens</h3>
                <h4>Speed / Strength</h4>
                <p>
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sequi neque animi quo cupiditate commodi saepe culpa
                  sed
                  itaque velit maiores optio dolorem excepturi aperiam dolores, voluptatibus suscipit amet quis repellat!
                </p>
              </div>
            </article>

            <!-- second trainer bio -->
            <article class="trainer">
              <div class="trainer-bio text-right">
                <h3>Joanna Gill</h3>
                <h4>Endurance</h4>
                <p>
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sequi neque animi quo cupiditate commodi saepe culpa
                  sed
                  itaque velit maiores optio dolorem excepturi aperiam dolores, voluptatibus suscipit amet quis repellat!
                </p>
              </div>
              <img src="./assets/images/trainer-2.jpg" alt="Joanna Gill cooling off after a workout"/>
            </article>

            <!-- third trainer bio -->
            <article class="trainer">
              <img src="./assets/images/trainer-3.jpg"
                alt="Harry Smith wearing a headband and lifting comically small pink weights" />
              <div class="trainer-bio text-left">
                <h3>Harry "the Headband" Smith</h3>
                <h4>Strength</h4>
                <p>
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sequi neque animi quo cupiditate commodi saepe culpa
                  sed
                  itaque velit maiores optio dolorem excepturi aperiam dolores, voluptatibus suscipit amet quis repellat!
                </p>
              </div>
            </article>
          </section>

#### CSS Code ရေးနည်း
.section-title {
  font-size: 55px;
  color: #024e76;
  margin-bottom: 35px;
  padding: 0 100px 20px 100px;
  display: inline-block;
  border-bottom: 3px solid;
}

.primary-border {
  border-color: #fce138;
}
(1-3 တွင်ပါပြီီးသားဖြစ်သည်)
.trainers {
  text-align: center;
}

.trainer {
  width: 900px;
  margin: 0 auto 30px auto;
  background: #024e76;
  color: #fce138;
  overflow: auto;
}

.trainer img {
  width: 35%;
  float: left;
}

.trainer-bio {
  padding: 35px;
  float: left;
  width: 65%;
}

.trainer-bio h3 {
  font-size: 32px;
  margin-bottom: 8px;
}

.trainer-bio h4 {
  font-weight: lighter;
  font-size: 26px;
  margin-bottom: 25px;
}

.trainer-bio p {
  font-size: 17px;
  line-height: 1.3;
}

.text-left {
  text-align: left;
}

.text-right {
  text-align: right;
}

# ✨(1-6)
- (1-6)ရဲ့ body ပိုင်းမှာ "Reach Out" section ကိုသင်ကြားပေးထားပါတယ်။
##  💡ရေးသားရမည့် ပုံစံ
![Read Out section](./image/(1-6)example.png)
## ရေးပုံရေးသားနည်း
- Reach Out section အတွက်  section tag ထဲတွင် id, class ပေးထားရမည်။
- section tag ထဲတွင် Reach Out title အတွက် h2 tagကိုသုံးရမည်။
- contact-info နှင့် map ကို section တစ်ခုထဲတွင် ပေါ်ချင်သောကြောင့် div tag အတွင်းရေးပေးရမည်။
- map ကို div tag အတွင်း ပေါ်ရန် imframe tag ကိုခေါ်ပြီး imframe tag အတွင်းတွင် မိမိထည့်ချင်သော address အတိအကျကို google map တွင် location အတိကျထောက်ပြီး url address ကို  src အတွင်းတွင် ကူးထည့်ပေးရမည်။(google map ပေါ်ရန် internet လိုအပ်တယ်) map size ပြောင်းရန် css တွင်  width, height ပြုပြင်ရမည်။
- div tag အတွင်း contact-info ကို တစ်စုထဲပေါ်ချင်သောကြောင့် နောက်ထပ် div tag တစ်ခုဖြင့်ရေးပေးရမည်။
- အသစ်ရေးထားသော div tag ထဲတွင် မိမိပေါ်ချင်သောအကြောင်းအရာများကို သက်ဆိုင်ရာ tag များအားထည့်ပြီးရေးပေးရမည်။ google map နှင့် contact-info ကို တစ်lineထဲ ပေါ်ချင်သောကြောင့်  css ထဲတွင် display: inline-block; ထည့်ရေးရမည်။ ပြင်ပြီးသား contact-info များသည် အောက်ကျနေသောကြောင့် vertical-align: top;ကို စာသားရွေ့ရန်သုံးပေးရမည်။
### HTML code ရေးနည်း
            <!-- "reach out" section -->
            <section id="reach-out" class="contact">
                <h2 class="section-title secondary-border">Reach Out</h2>
                <div class="contact-info">
                <iframe
                    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3147.1079747227936!2d-120.42364418397035!3d37.92790791110593!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8090c49129b6ac57%3A0xb56c7eb95a2cd8bd!2sMain%20St%2C%20California%2095327!5e0!3m2!1sen!2sus!4v1616426329495!5m2!1sen!2sus"
                    style="border:0;"
                    allowfullscreen=""
                    loading="lazy">
                </iframe>
                <div>
                    <h3>Run Buddy</h3>
                    <p>
                    Any questions or concerns before signing up?
                    <br />
                    Let us know and we'll be happy to talk to you!
                    </p>
                    <address>
                    55 Main Street <br />
                    Some Town, Ca <br />
                    12345<br />
                    P: 555.RUN.BUDZ (555.786.2839)<br />
                    E: <a href="mailto:info@runbuddy.io">info@runbuddy.io</a>
                    </address>
                </div>
                </div>
            </section>
### CSS code ရေးနည်း
            /* REACH OUT STYLES START */
            .contact {
            text-align: center;
            background: #024E76;
            }
            .contact h2 {
            color: #FCE138;
            }
            .contact-info iframe {
            width: 400px;
            height: 400px;
            }
            .contact-info div {
            width: 410px;
            display: inline-block;
            vertical-align: top;
            text-align: left;
            margin: 30px 0 0 60px;
            color: white;
            }
            .contact-info h3 {
            color: #FCE138;
            font-size: 32px;
            }
            .contact-info p,
            .contact-info address {
            margin: 20px 0;
            line-height: 1.5;
            font-size: 20px;
            font-style: normal;
            }
            .contact-info a {
            color: #FCE138;
            }
            /* REACH OUT STYLES END */