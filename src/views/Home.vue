<template>
  <div>
    <div class="header">
      <h1>منصة أقلام التعليمية لوريم ايبسوم دولار سيت</h1>
      <h4>
        منصة أقلام التعليمية لوريم ايبسوم دولار سيت أميت ,كونسيكتيتور أدايبا
        يسكينج أليايت,سيت دو أيوسمود تيمبور
      </h4>
      <div class="search-bar">
        <button>
          <svg
            id="search-duotone_1_"
            data-name="search-duotone (1)"
            xmlns="http://www.w3.org/2000/svg"
            width="31.944"
            height="31.95"
            viewBox="0 0 31.944 31.95"
          >
            <path
              id="Path_67015"
              data-name="Path 67015"
              d="M12.978,4.992A7.987,7.987,0,1,1,7.331,7.331a7.987,7.987,0,0,1,5.647-2.339m0-4.992A12.978,12.978,0,1,0,25.957,12.978,12.978,12.978,0,0,0,12.978,0Z"
              transform="translate(0)"
              fill="#fff"
              opacity="0.4"
            />
            <path
              id="Path_67016"
              data-name="Path 67016"
              d="M346.539,344.779l-1.766,1.766a1.491,1.491,0,0,1-2.115,0l-6.221-6.221a1.5,1.5,0,0,1-.437-1.061v-1.017L338.246,336h1.017a1.5,1.5,0,0,1,1.061.437l6.221,6.221A1.5,1.5,0,0,1,346.539,344.779Z"
              transform="translate(-315.035 -315.035)"
              fill="#fff"
            />
          </svg>
        </button>
        <input
          type="text"
          placeholder="ابحث عن كل ما تريده من كورسات و محاضرين"
        />
      </div>
    </div>
    <!-- services -->
    <div class="services">
      <div class="service" v-for="(service, index) in services" :key="index">
        <img :src="service.pic" alt="" />
        <p>{{ service.text }}</p>
      </div>
    </div>
    <!-- features -->
    <div class="features-sec">
      <div class="fea-text">
        <h2>ماذا يميز أقلام عن باقي المنصات؟</h2>
        <p>
          لدينا ما يكفي من المميزات التي تفصلنا عن غيرنا من المنصات لدينا ما
          يكفي من المميزات التي تفصلنا عن غيرنا من المنصات لدينا ما يكفي من
          المميزات
        </p>
      </div>
      <div class="features">
        <div class="feat-wrap up">
          <div class="feat">
            <h1>01</h1>
            <h4>لوريم ايبسوم دولار سيت أميت</h4>
            <p>
              "منصة أقلام التعليمية لوريم ايبسوم دولار سيت أميت ,كونسيكتيتور
              أدايبا يسكينج",
            </p>
          </div>
        </div>
        <div class="feat-wrap">
          <div class="feat">
            <h1>02</h1>
            <h4>لوريم ايبسوم دولار سيت أميت</h4>
            <p>
              "منصة أقلام التعليمية لوريم ايبسوم دولار سيت أميت ,كونسيكتيتور
              أدايبا يسكينج",
            </p>
          </div>
        </div>
        <div class="feat-wrap down">
          <div class="feat">
            <h1>03</h1>
            <h4>لوريم ايبسوم دولار سيت أميت</h4>
            <p>
              "منصة أقلام التعليمية لوريم ايبسوم دولار سيت أميت ,كونسيكتيتور
              أدايبا يسكينج",
            </p>
          </div>
        </div>
      </div>
      <div class="features">
        <div class="feat-wrap up">
          <div class="feat">
            <h1>04</h1>
            <h4>لوريم ايبسوم دولار سيت أميت</h4>
            <p>
              "منصة أقلام التعليمية لوريم ايبسوم دولار سيت أميت ,كونسيكتيتور
              أدايبا يسكينج",
            </p>
          </div>
        </div>
        <div class="feat-wrap">
          <div class="feat">
            <h1>05</h1>
            <h4>لوريم ايبسوم دولار سيت أميت</h4>
            <p>
              "منصة أقلام التعليمية لوريم ايبسوم دولار سيت أميت ,كونسيكتيتور
              أدايبا يسكينج",
            </p>
          </div>
        </div>
        <div class="feat-wrap down">
          <div class="feat">
            <h1>06</h1>
            <h4>لوريم ايبسوم دولار سيت أميت</h4>
            <p>
              "منصة أقلام التعليمية لوريم ايبسوم دولار سيت أميت ,كونسيكتيتور
              أدايبا يسكينج",
            </p>
          </div>
        </div>
      </div>
    </div>
    <!-- teachers -->
    <div class="teachers-sec">
      <div class="teach-text">
        <h1>محاضرين مختصين</h1>
        <p>جمعنا لكم اكبر فئة من المحاضرين المختصين لتجدوهم بمنصة واحدة</p>
      </div>
      <div class="teachers">
        <div class="teacher" v-for="(teacher, index) in teachers" :key="index">
          <img :src="teacher.pic" alt="" />
          <img :src="tele" alt="" class="tele" />
          <h3>{{ teacher.name }}</h3>
          <h4>{{ teacher.subject }}</h4>
          <div class="teach-info">
            <div class="cors">
              <p>20</p>
              <h4>دورة</h4>
            </div>
            <div class="files">
              <p>80</p>
              <h4>ملف</h4>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- card -->
    <div class="card">
      <div class="wrap">
        <div class="card-desc">
          <h1>ماذا تريد أن تتعلم اليوم؟</h1>
          <p>
            نقدم قيم مختلفة من بطاقات الشراء و التعبئة التي تمكنك من الحصول على
            أي كورس بالقيمة التي تريدها
          </p>
        </div>
        <img src="../assets/cards.png" alt="" />
        <button>تعرف على نقاط بيع البطاقات</button>
      </div>
    </div>
    <!-- courses -->
    <div class="cors-wrap">
      <h1>كورسات متنوعة الفئات</h1>
      <p>جمعنا لكم اكبر مجموعة من الكورسات المتنوعة و المختلفة</p>
      <div class="courses">
        <div class="course" v-for="(cors, index) in courses" :key="index">
          <img src="../assets/cors-pic.png" alt="" />
          <p class="label">{{ cors.label }}</p>
          <h3>{{ cors.title }}</h3>
          <div class="pen">
            <p>بقلم</p>
            <img :src="pen" alt="" />
          </div>
          <div class="who">
            <p>{{ cors.teacher }}</p>
            <img src="../assets/ahmad.png" alt="" />
          </div>
          <div class="price">
            <h3>دينار أردني</h3>
            <h2>{{ cors.price }}</h2>
          </div>
          <div class="btns">
            <img :src="watch" alt="" class="watch" />
            <button>اشتري الدورة</button>
          </div>
        </div>
      </div>
    </div>
    <!-- join us -->
    <div class="join">
      <div class="join-text">
        <h3>ماذا تنتظر؟</h3>
        <p>
          إلى جانب حساب طالب , أقلام يتيح لك فرصة إنشاء حساب معلم لتتمكن من رفع
          الكورسات التي تريد تعليمها في أي وقت و من أي محتوى تريده
        </p>
        <button>أنشئ حسابك الآن</button>
      </div>
    </div>
    <!-- footer -->
    <div class="footer">
      <div class="row">
        <div class="media">
          <img :src="face" alt="" />
          <img :src="twitter" alt="" />
          <img :src="insta" alt="" />
        </div>
        <div class="links">
          <router-link to="">الشروط و الأحكام</router-link>
          <router-link to="">الدعم الفني</router-link>
          <router-link to="">من نحن</router-link>
          <router-link to="">خريطة الموقع</router-link>
        </div>
        <div class="logo">
          <img :src="logo" alt="" />
        </div>
      </div>
      <p>جميع الحقوق محفوظة لدى &copy; أقلام</p>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
  data() {
    return {
      tele: require("./svgs/tele.svg"),
      watch: require("./svgs/watch.svg"),
      pen: require("./svgs/pen.svg"),
      logo: require("./svgs/logo.svg"),
      face: require("./svgs/facebook.svg"),
      twitter: require("./svgs/twitter.svg"),
      insta: require("./svgs/insta.svg"),
      services: [
        { text: "الدعم الفني", pic: require("./svgs/support.svg") },
        { text: "من نحن", pic: require("./svgs/we.svg") },
        { text: "المكتبة", pic: require("./svgs/libary.svg") },
        { text: "الملفات", pic: require("./svgs/files.svg") },
        {
          text: "الكورسات",
          pic: require("./svgs/cors.svg")
        }
      ],
      features: [
        {
          no: "03",
          title: "لوريم إبسوم دولار",
          desc:
            "منصة أقلام التعليمية لوريم ايبسوم دولار سيت أميت ,كونسيكتيتور أدايبا يسكينج"
        },
        {
          no: "02",
          title: "لوريم إبسوم دولار",
          desc:
            "منصة أقلام التعليمية لوريم ايبسوم دولار سيت أميت ,كونسيكتيتور أدايبا يسكينج"
        },
        {
          no: "01",
          title: "لوريم إبسوم دولار",
          desc:
            "منصة أقلام التعليمية لوريم ايبسوم دولار سيت أميت ,كونسيكتيتور أدايبا يسكينج"
        },
        {
          no: "06",
          title: "لوريم إبسوم دولار",
          desc:
            "منصة أقلام التعليمية لوريم ايبسوم دولار سيت أميت ,كونسيكتيتور أدايبا يسكينج"
        },
        {
          no: "05",
          title: "لوريم إبسوم دولار",
          desc:
            "منصة أقلام التعليمية لوريم ايبسوم دولار سيت أميت ,كونسيكتيتور أدايبا يسكينج"
        },
        {
          no: "04",
          title: "لوريم إبسوم دولار",
          desc:
            "منصة أقلام التعليمية لوريم ايبسوم دولار سيت أميت ,كونسيكتيتور أدايبا يسكينج"
        }
      ],
      teachers: [
        {
          name: "جميل جمال جملون الجميل",
          subject: "أستاذ رياضيات",
          pic: require("../assets/teach1.png")
        },
        {
          name: "جميل جمال جملون الجميل",
          subject: "أستاذ رياضيات",
          pic: require("../assets/teach2.png")
        },
        {
          name: "جميل جمال جملون الجميل",
          subject: "أستاذ رياضيات",
          pic: require("../assets/teach3.png")
        },
        {
          name: "جميل جمال جملون الجميل",
          subject: "أستاذ رياضيات",
          pic: require("../assets/teach4.png")
        },
        {
          name: "جميل جمال جملون الجميل",
          subject: "أستاذ رياضيات",
          pic: require("../assets/teach5.png")
        }
      ],
      courses: [
        {
          title: "الجسم البشري و الطب الحديث",
          label: "مهارات عملية",
          price: "50",
          teacher: "خليل أحمد"
        },
        {
          title: "الجسم البشري و الطب الحديث",
          label: "مهارات عملية",
          price: "50",
          teacher: "خليل أحمد"
        },
        {
          title: "الجسم البشري و الطب الحديث",
          label: "مهارات عملية",
          price: "50",
          teacher: "خليل أحمد"
        },
        {
          title: "الجسم البشري و الطب الحديث",
          label: "مهارات عملية",
          price: "50",
          teacher: "خليل أحمد"
        },
        {
          title: "الجسم البشري و الطب الحديث",
          label: "مهارات عملية",
          price: "50",
          teacher: "خليل أحمد"
        }
      ]
    };
  }
};
</script>
<style lang="scss" scoped>
.header {
  padding: 0 5%;
  h1,
  h4 {
    margin: 2rem 0 !important;
  }
  .search-bar {
    display: flex;
    align-items: center;
    justify-content: center;
    button {
      background-color: #fea403;
      border: none;
      padding: 0.7rem 1rem;
      border-radius: 5px;
      cursor: pointer;
    }
    input {
      height: 2rem;
      width: 20%;
      border-radius: 5px;
      border: none;
      text-align: right;
      padding: 0.5rem;
    }
    ::placeholder {
      color: grey;
      opacity: 1; /* Firefox */
    }

    :-ms-input-placeholder {
      /* Internet Explorer 10-11 */
      color: grey;
    }

    ::-ms-input-placeholder {
      /* Microsoft Edge */
      color: grey;
    }
  }
}
.services {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  align-items: center;
  margin: 5% 0;
  padding: 1rem 0;
  .service {
    background-color: white;
    box-sizing: border-box;
    cursor: pointer;
    border-radius: 7px;
    padding: 1rem;
    margin: 0.5rem 0;
    width: 157px;
    height: 157px;
    display: flex;
    align-items: center;
    justify-content: space-around;
    flex-direction: column;
    &:hover {
      border: 1px solid #fea403;
    }
    p {
      margin: 0;
    }
  }
}
.features-sec {
  padding: 0 5%;
  .fea-text {
    text-align: right;
    width: 30%;
    margin: 0;
    p {
      color: #fea403;
      font-weight: bold;
      font-size: 0.8rem;
    }
  }
  .features {
    display: flex;
    flex-wrap: wrap;
    flex-direction: row-reverse;
    margin: 0;
    justify-content: space-between;
    align-items: center;
    .feat-wrap {
      flex-basis: 30%;
      margin: 0;
      .feat {
        width: 45%;
        margin: 2% auto;
        background-color: white;
        text-align: right;
        border-radius: 8px;
        padding: 2rem 1rem;
        position: relative;
        h1 {
          font-size: 4rem;
          position: absolute;
          top: -35%;
          right: 0;
        }
        h1,
        p {
          color: rgb(187, 187, 187);
          font-weight: bold;
        }
        p {
          font-size: 0.8rem;
        }
        h4,
        p,
        h1 {
          margin: 0.5rem 0;
        }
      }
    }
    .up {
      padding-bottom: 20% !important;
    }
    .down {
      padding-top: 20% !important;
    }
  }
}
.teachers-sec {
  padding: 0 5%;
  .teach-text {
    text-align: right;
    p {
      color: #fea403;
      font-weight: bold;
    }
  }
  .teachers {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    align-items: center;
    gap: 2rem;
    .teacher {
      background-color: white;
      padding: 7% 1rem 2% 1rem;
      border-radius: 8px;
      margin: 7% 0;
      position: relative;
      h4 {
        color: rgb(187, 187, 187);
        margin: 0.5rem 0;
      }
      p,
      h3 {
        font-weight: bold;
        margin: 0;
      }
      img {
        position: absolute;
        top: -25%;
        left: -2%;
        height: 8rem;
        width: 8rem;
      }
      .tele {
        width: 3rem;
        height: 3rem;
        position: absolute;
        top: 5%;
        left: 40%;
        cursor: pointer;
      }
      .teach-info {
        display: flex;
        justify-content: space-around;
      }
    }
  }
}
.card {
  background: url("../assets/bg.png");
  background-size: cover;
  background-repeat: no-repeat;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: flex-start;
  flex-direction: column;
  padding: 0 5%;
  .wrap {
    padding: 0 5%;
    width: 35%;
    .card-desc {
      text-align: right;
      p {
        color: #fea403;
        font-weight: bold;
      }
    }
    img {
      width: 100%;
    }
    button {
      border: none;
      background-color: #012e43;
      color: white;
      padding: 0.5rem 2rem;
      font-size: 1.2rem;
      font-weight: bold;
      border-radius: 8rem;
      margin: 5% 0;
      cursor: pointer;
    }
  }
}
.cors-wrap {
  h1 {
    color: #012e43;
  }
  p {
    color: #fea403;
    font-weight: bold;
  }
  .courses {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    .course {
      background-color: white;
      padding: 1rem;
      text-align: right;
      position: relative;
      border-radius: 12px;
      .label {
        background-color: #fea403;
        color: white;
        position: absolute;
        top: 5%;
        right: -1%;
        padding: 0 0.5rem;
        font-weight: bold;
      }
      .btns {
        display: flex;
        justify-content: space-between;
        align-items: center;
      }
      .pen,
      .who,
      .price {
        display: flex;
        justify-content: flex-end;
        align-items: center;
        img {
          margin: 0 0 0 0.5rem;
          object-fit: contain;
        }
        h2,
        h3 {
          margin: 0 0.5rem !important;
          color: #fea403;
        }
      }
      button {
        border: none;
        background-color: #012e43;
        color: white;
        padding: 0.5rem 2rem;
        font-size: 1.2rem;
        font-weight: bold;
        border-radius: 8rem;
        margin: 5% 0;
        cursor: pointer;
      }
      .watch {
        background-color: #f4f4f4;
        padding: 0 1rem;
        border-radius: 2rem;
        cursor: pointer;
      }
    }
  }
}
.join {
  background-color: #012e43;
  padding: 2rem 5%;
  margin: 10% 0;
  .join-text {
    h3 {
      color: white;
    }
    p {
      color: #fea403;
      font-weight: bold;
    }
    button {
      border: none;
      padding: 0.5rem 2rem;
      border-radius: 8rem;
      font-weight: bold;
      cursor: pointer;
    }
  }
}
.footer {
  .row {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    align-items: center;
    .links {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      align-items: center;
      gap: 2rem;
      a {
        text-decoration: none;
        color: #012e43;
        font-weight: bold;
      }
    }
    .media {
      img {
        margin: 0 0.5rem;
      }
    }
  }
  p {
    color: #b7b7b7;
    font-weight: bold;
  }
}
// media quiries
@media screen and (min-width: 320px) and (max-width: 567px) {
  .header {
    h1,
    h4 {
      margin: 1rem 0 !important;
    }
    .search-bar {
      input {
        width: 100%;
      }
    }
  }
  .features-sec {
    .fea-text {
      width: 100%;
    }
    .features {
      .feat-wrap {
        flex-basis: 100%;
        .feat {
          width: 75%;
          margin: 5% auto;
          padding: 1rem;
          h1 {
            position: relative;
          }
        }
      }
      .up,
      .down {
        padding: 0 !important;
      }
    }
  }
  .teachers {
    margin: 10% 0;
    .teacher {
      margin: 15% 0 !important;
      padding: 25% 3% 5% 3% !important;
    }
  }
  .card {
    .wrap {
      width: 90% !important;
    }
  }
  .course {
    margin: 5% 0;
  }
}
@media screen and (min-width: 568px) and (max-width: 767px) {
  .header {
    h1,
    h4 {
      margin: 1rem 0 !important;
    }
    .search-bar {
      input {
        width: 100%;
      }
    }
  }
  .features-sec {
    .fea-text {
      width: 100%;
    }
    .features {
      .feat-wrap {
        flex-basis: 100%;
        .feat {
          width: 75%;
          margin: 5% auto;
          padding: 1rem;
          h1 {
            position: relative;
          }
        }
      }
      .up,
      .down {
        padding: 0 !important;
      }
    }
  }
  .teachers {
    margin: 10% 0;
    .teacher {
      margin: 5% 0 !important;
      padding: 15% 3% 5% 3% !important;
    }
  }
  .card {
    .wrap {
      width: 60% !important;
    }
  }
  .course {
    margin: 5% 0;
  }
}
@media screen and (min-width: 768px) and (max-width: 991px) {
  .header {
    h1,
    h4 {
      margin: 1rem 0 !important;
    }
    .search-bar {
      input {
        width: 50%;
      }
    }
  }
  .features-sec {
    .features {
      .feat-wrap {
        .feat {
          width: 75%;
          margin: 5% auto;
          padding: 1.5rem;
          h1 {
            font-size: 4rem;
            position: absolute;
            top: -36%;
            right: 0;
          }
        }
      }
    }
  }
  .teachers {
    margin: 10% 0;
    .teacher {
      margin: 5% 0 !important;
      padding: 10% 3% 5% 3% !important;
    }
  }
  .card {
    .wrap {
      width: 50% !important;
    }
  }
  .course {
    margin: 5% 0;
  }
}
@media screen and (min-width: 992px) and (max-width: 1200px) {
  .header {
    h1,
    h4 {
      margin: 1rem 0 !important;
    }
    .search-bar {
      input {
        width: 30%;
      }
    }
  }
  .features-sec {
    .features {
      .feat-wrap {
        .feat {
          width: 55%;
          margin: 5% auto;
          padding: 1.5rem;
          h1 {
            font-size: 4rem;
            position: absolute;
            top: -35%;
            right: 0;
          }
        }
      }
    }
  }
  .teachers {
    margin: 10% 0;
    .teacher {
      margin: 5% 0 !important;
      padding: 9% 3% 5% 3% !important;
    }
  }
  .card {
    .wrap {
      width: 50% !important;
    }
  }
  .course {
    margin: 2% 0;
  }
}
</style>
