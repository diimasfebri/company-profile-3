<template>
<div class="container">
    <div class="slide-one">
        <img class="bg-content" src="https://images.unsplash.com/uploads/1412273646059cc129bb5/eae0a1da?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80">
        <div class="desc-container">
            <span class="desc">LET'S BE BROS</span>
            <span class="desc-1">TELL US MORE</span>
        </div>
      </div>
    <div class="slide-two">
        <span class="desc">WHAT SERVICES DO YOU NEED?</span>
        <div class="button-list">
            <div class="button"  >
                <div class="circle"></div>
                <span class="txt">I NEED A FREASH LOOK (Our design team is ready!)</span>
            </div>
            <div class="button active">
                <div class="circle"></div>
                <span class="txt">MY DESIGN ARE READY TO GO (Upload assets below)</span>
            </div>
        </div>
        <div class="button-list-sec">
            <span class="desc">DESIGN SERVICES</span>
            <div class="desc-container">
                <div class="button">
                    <div class="circle">
                        <div class="bg"></div>
                    </div>
                    <span class="txt">ILLUSTRATION</span>
                </div>
                <div class="button">
                    <div class="circle">
                        <div class="bg"></div>
                    </div>
                    <span class="txt">PACKAGE AND LABEL DESIGN</span>
                </div>
                <div class="button">
                    <div class="circle">
                        <div class="bg"></div>
                    </div>
                    <span class="txt">LOGO/BRANDING</span>
                </div>
            </div>
        </div>
        <div class="product">
        <span class="desc">CATEGORIES</span>
        <div class="card-list">
            <div class="card">
            <img src="https://images.prismic.io/andersonbrothers/89d584b8-3691-4255-80d4-b8ebcd5b1350_John-Anderson-President.jpg?auto=compress,format&w=330&h=370&fit=crop&q=85&f=center" alt="">
            <span class="name"> TEES </span>
            <div class="button"></div>
            </div>
            <div class="card">
            <img src="https://images.prismic.io/andersonbrothers/83eae39b-48fb-4e72-a27e-edf48fbd5425_Mike-Anderson-Creative-Director.jpg?auto=compress,format&w=330&h=370&fit=crop&q=85&f=center" alt="">
            <span class="name"> FLEECE </span>
            <div class="button"></div>
            </div>
            <div class="card">
            <img src="https://images.prismic.io/andersonbrothers/29830ffb-eb83-48d0-9830-d53bf63574d5_Aaron-Ashton-Sales-%26-Marketing.jpg?auto=compress,format&w=330&h=370&fit=crop&q=85&f=center" alt="">
            <span class="name"> FLANNELS </span>
            <div class="button"></div>
            </div>
            </div>  
        <div class="card-list two">
            <div class="card">
            <img src="https://images.prismic.io/andersonbrothers/6eb97008-65a2-427b-ab41-a835617f3abb_AfterlightImage+22.JPG?auto=compress,format&w=330&h=370&fit=crop&q=85&f=center" alt="">
            <span class="name"> OUTERWEAR/JACKET </span>
            <div class="button"></div>
            </div>
            <div class="card">
            <img src="https://images.prismic.io/andersonbrothers/bd632467-16f3-429a-abdc-a342cf41c708_Debbi-Wong-Accounting-Manager.jpg?auto=compress,format&w=330&h=370&fit=crop&q=85&f=center" alt="">
            <span class="name"> HEADWEAR </span>
            <div class="button"></div>
            </div>
            <div class="card">
            <img src="https://images.prismic.io/andersonbrothers/2117d343-7156-4e6f-9002-090ea6342e42_Kenny-Novak-Graphic-Design.jpg?auto=compress,format&w=330&h=370&fit=crop&q=85&f=center" alt="">
            <span class="name"> GLASSWEAR/GROWLERS </span>
            <div class="button"></div>
            </div>
            </div>  
        <div class="card-list test">
            <div class="card">
            <img src="https://images.prismic.io/andersonbrothers/4ecfbc98-ced8-40ae-8082-ea5c65e06ba8_Madison-Bailey-Production-Manager.jpg?auto=compress,format&w=330&h=370&fit=crop&q=85&f=center" alt="">
            <span class="name"> ACCESSORIES </span>
            <div class="button"></div>
            </div>
            <div class="card">
            <img src="https://images.prismic.io/andersonbrothers/e600c588-2fed-4de6-933a-68406fc2d409_Tempest-Orman-Accounting-Asst.jpg?auto=compress,format&w=330&h=370&fit=crop&q=85&f=center" alt="">
            <span class="name"> PROMOTIONAL </span>
            <div class="button"></div>
            </div>
            </div>   
        </div>

      </div>
    <div class="slide-three">
        <span class= "desc">LETS WORK TOGETHER</span>
        <div class="form">
            <input type="text" name="" required placeholder="First Name" >
            <input type="text" name="" required placeholder="Last Name" >
            <input type="text" name="" required placeholder="Company" >
            <input type="email" name="" required placeholder="Email" >
            <input type="text" name="" required placeholder="Phone" >
            <div class="upload-container">
                <span class="upload">Upload Brand Assets And Logo</span>
                <div class="button">
                    <span class="unggah">UPLOAD</span>
                </div>
            </div>
            <div class="buttongede" @click="$router.push('/confirmed')">
                <span class="kumpul">SUBMIT!</span>
            </div>
            <span class= "desc-2">PULL THE TRIGGER</span>
        </div>
      </div>
    <div class="slide-four">
     <div class="bg">
        <div class="line" aria-hidden="true">
          <img  src="https://images.prismic.io/andersonbrothers/18c63e8b-da67-4e14-a575-73a6a68ceef5_logos-row-1.png?auto=compress,format">
          <img  src="https://images.prismic.io/andersonbrothers/18c63e8b-da67-4e14-a575-73a6a68ceef5_logos-row-1.png?auto=compress,format">
          <img  src="https://images.prismic.io/andersonbrothers/18c63e8b-da67-4e14-a575-73a6a68ceef5_logos-row-1.png?auto=compress,format">
          <img  src="https://images.prismic.io/andersonbrothers/18c63e8b-da67-4e14-a575-73a6a68ceef5_logos-row-1.png?auto=compress,format">
        </div>
        <div class="line x" aria-hidden="true">
          <img  src="https://images.prismic.io/andersonbrothers/c75ffffc-ec43-4da8-9b3a-f6f31a16c508_logos-row-2.png?auto=compress,format">
          <img  src="https://images.prismic.io/andersonbrothers/c75ffffc-ec43-4da8-9b3a-f6f31a16c508_logos-row-2.png?auto=compress,format">
          <img  src="https://images.prismic.io/andersonbrothers/c75ffffc-ec43-4da8-9b3a-f6f31a16c508_logos-row-2.png?auto=compress,format">
          <img  src="https://images.prismic.io/andersonbrothers/c75ffffc-ec43-4da8-9b3a-f6f31a16c508_logos-row-2.png?auto=compress,format">
        </div>
        <div class="line" aria-hidden="true">
          <img  src="https://images.prismic.io/andersonbrothers/30940b70-234d-4557-8554-5bc4355e6742_abds_logos_row3b.png?auto=compress,format">
          <img  src="https://images.prismic.io/andersonbrothers/30940b70-234d-4557-8554-5bc4355e6742_abds_logos_row3b.png?auto=compress,format">
          <img  src="https://images.prismic.io/andersonbrothers/30940b70-234d-4557-8554-5bc4355e6742_abds_logos_row3b.png?auto=compress,format">
          <img  src="https://images.prismic.io/andersonbrothers/30940b70-234d-4557-8554-5bc4355e6742_abds_logos_row3b.png?auto=compress,format">
        </div>
        <div class="line x" aria-hidden="true">
          <img  src="https://images.prismic.io/andersonbrothers/3fc617ce-03d0-4221-bca4-7fc328d3f9cc_logos-row-4.png?auto=compress,format">
          <img  src="https://images.prismic.io/andersonbrothers/3fc617ce-03d0-4221-bca4-7fc328d3f9cc_logos-row-4.png?auto=compress,format">
          <img  src="https://images.prismic.io/andersonbrothers/3fc617ce-03d0-4221-bca4-7fc328d3f9cc_logos-row-4.png?auto=compress,format">
          <img  src="https://images.prismic.io/andersonbrothers/3fc617ce-03d0-4221-bca4-7fc328d3f9cc_logos-row-4.png?auto=compress,format">
        </div>  
      </div>
    </div>
</div>
</template>

<script>
export default {
 data(){
    return{
      buttonSelected: false,
        
    }
}
}
</script>
<style lang="scss" scoped>

.container{
  position: relative;
  width: 100vw;
  min-height: 100vh;
  min-height: calc((var(--vh, 1vh) * 100));
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  overflow: hidden;
  overflow-y: auto;
  overflow: hidden;
   > * {
    flex-shrink: 0;
  }
  .slide-one{
    position: relative;
    width: 100vw;
    height: 100vh;
    display: flex;
    img.bg-content{
      position: absolute;
      width: 100vw;
      height: 80vh;
      object-fit: cover;
    }
    .desc-container{
        position: relative;
        display: flex;
        width: 100%;
        height: 100%;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    span.desc{
        font-family: Antonio;
        color: white;
        font-size: 3rem;
        font-weight: 900;
    }
    span.desc-1{
        font-family: Antonio;
        color: white;
        font-size: 0.7rem;
        font-weight: 900;
        margin-top: 1rem;
    }
    }
    }
  .slide-two{
    position: relative;
    width: 100vw;
    display: flex;
    color: white;
    align-items: center;
    justify-content: flex-start;
    flex-direction: column;
    span.desc{
        text-align: center;
        font-family: Antonio;
        color: black;
        font-size: 1.7rem;
        font-weight: 900;
    }
    .button-list{
    position: relative;
    display: flex;
    margin-top: 2rem;
    width: 60%;
    flex-direction: row;
    justify-content: space-between;
    align-items: space-between;
     .button{
         position: relative;
         display: flex;
         width: 22rem;
         height: 2.5rem;
         border: 5px solid black;
         flex-direction: row;
         justify-content: flex-start;
         align-items: center;
            .circle{
            position: relative;
            display: flex;
            width: 1.5rem;
            height: 1.5rem;
            border: 5px solid black;
            border-radius: 100%;
            margin: 0 0.5rem;
            }
            span.txt{
                justify-content: flex-start;
                align-items: flex-start;
                font-family: Quicksand;
                color: black;
                font-size: 0.7rem;
                border: black;
            }
            &:active{
                .button{
                border: 5px solid #b48645;
            
                }
            }   
     }
    
    }
    .button-list-sec{
    position: relative;
    display: flex;
    margin-top: 2rem;
    width: 80%;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    span.desc{
        text-align: center;
        font-family: Antonio;
        color: black;
        font-size: 1rem;
        font-weight: bold; 
    }
    .desc-container{
        position: relative;
        display: flex;
        flex-direction: row;
        justify-content: flex-start;
        align-items: center;
     .button{
         position: relative;
         display: flex;
         width: 13rem;
         height: 2.5rem;
         border: 5px solid black;
         flex-direction: row;
         justify-content: flex-start;
         align-items: center;
         margin: 0 0.5rem;
         margin-top: 1rem;
        .circle{
          position: relative;
          display: flex;
          width: 2.5rem;
          height: 2.8rem;
          border-right: 5px solid black;
          margin-right: 1rem;
          justify-content: center;
          align-items: center;
          .bg{
            width: 100%;
            height: 90%;
            background: #f0eee3;
          }
        }
        span.txt{
            justify-content: flex-start;
            align-items: flex-start;
            font-family: Quicksand;
            color: black;
            font-size: 0.7rem;
            border: black;
        }
     }
    
     .button-1{
         position: relative;
         display: flex;
         width: 22rem;
         height: 2.5rem;
         margin-left: 1rem;
         border: 5px solid black;
         flex-direction: row;
         justify-content: flex-start;
         align-items: center;
     .circle{
          position: relative;
          display: flex;
          width: 1.5rem;
          height: 1.5rem;
          border: 5px solid black;
          border-radius: 100%;
          margin: 0 0.5rem;
        }
        span.txt{
            justify-content: flex-start;
            align-items: flex-start;
            font-family: Quicksand;
            color: black;
            font-size: 0.7rem;
            border: black;
        }
    }
    }
  
    }
    .product{
    position: relative;
    display: flex;
    margin-top: 2rem;
    margin-bottom: 3rem;
    width: 80%;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
     span.desc{
        text-align: center;
        font-family: Antonio;
        color: black;
        font-size: 1rem;
        margin: 1.5rem 0;
        font-weight: 900; 
        }
     .card-list{
    position: relative;
    width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
      .card{
        position: relative;
        display: flex;
     
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        img{
          position: relative;
          display: flex;
          flex-direction: column;
          justify-content: flex-start;
          align-items: flex-start;
          margin-left: 0.5rem;
        }
        span.name{
          position: relative;
          font-family: 'Quicksand';
          font-size: 0.7rem;
          font-weight: 600;
          margin-left :4rem;
          justify-content: flex-start;
          align-items: flex-start;
          display: flex;
          transform: translateY(-3rem);
        }
        .button{
            position: relative;
            display: flex;
            transform: translateY(-4.8rem);
            height: 2rem;
            margin-left: 1.5rem;
            width: 2rem;
            border: 4px solid black;
            background: white;
      }
      }

     
     }
    }
    }
  .slide-three{
    position: relative;
    display: flex;
    width: 100vw;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    span.desc{
         text-align: center;
        font-family: 'Antonio';
        color: black;
        margin: 1rem 0;
        font-size: 1.7rem;
        font-weight: 900;
    }
    .form{
        position: relative;
        display: flex;
        width: 100%;
        flex-direction: column;
        justify-content: flex-start;
        align-items: center;
        input{
            height: 2rem;
            width: 24rem;
            margin-bottom: 0.5rem;
            border-bottom: 1px solid #b48645;       
            outline: none;
        }
    }
    .upload-container{
        position: relative;
        display: flex;
        width: 24rem;
        height: 2.8rem;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        border-bottom: 1px solid #b48645;       
        span.upload{
            text-align: center;
            font-family: 'Quicksand';
            color: black;
            font-size: 0.7rem;
            font-weight: 900;  
       }
       .button{
           position: relative;
           display: flex;
           justify-content: center;
           align-items: center;
           background: #282829;
           height: 1.5rem;
           width: 3rem;
           span.unggah{
            text-align: center;
            font-family: Antonio;
            color: white;
            font-size: 0.7rem;
            font-weight: 900;
           }
           &:hover{
               background: #b48645;
           }
          
       }
    }
     .buttongede{
                position: relative;
                display: flex;
                justify-content: center;
                align-items: center;
                background: #b48645;
                height: 5rem;
                width: 24rem;
                margin: 2rem 0;

               span.kumpul{
                   text-align: center;
                    font-family: 'Antonio';
                    color: white;
                    margin: 1rem 0;
                    font-size: 1.7rem;
                    font-weight: 900;
               }
               &:hover{
                   background: #282829;
               }
           }
     span.desc-2{
            text-align: center;
            font-family: 'Antonio';
            color: black;
            font-size: 6rem;
            font-weight: 900; 
            font-weight: bold; 
            margin-bottom: 2rem;

     }
    }
  .slide-four{
   position: relative;
      display: flex;
      padding: 2rem 0;
      width: 100vw;
      flex-direction: column;
      justify-content: flex-start;
      align-items: center;
      background:#282829 ;
      .bg {
      position: relative;
      overflow: hidden;
      --offset: 20vw;
      --move-initial: calc(-25% + var(--offset));
      --move-final: calc(-50% + var(--offset));
      .line{
        width: fit-content;
        display: flex;
        position: relative;
        transform: translate3d(var(--move-initial), 0, 0);
        animation: marquee 20s linear infinite;
        animation-play-state: running;
        img{
          height: 6rem;
          padding: 1rem 2px;
        }
        @keyframes marquee {
        0% {
            transform: translate3d(var(--move-initial), 0, 0);
        }
        100% {
            transform: translate3d(var(--move-final), 0, 0);
        }
        } 
        &.x{
        animation-direction: reverse;
        }       
      }
    }
  }
  }

</style>