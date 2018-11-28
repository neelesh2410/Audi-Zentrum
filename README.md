# Audi-Zentrum
 signIn(form:NgForm) {
    
    // if(this.uname.value === "admin" && this.password.value === "admin" ){
    //   console.log('User logged in.');
    //   let alert = this.alertCtrl.create({
    //     title: 'Login Successfu!',
    //     subTitle: 'You are logged in', 
    //     buttons: ['ok']
    //   });
    //   alert.present();
    // }
    
    
    // if(this.username === "admin" && this.pwd === "admin" ) {
      console.log('User logged in.');
      
        this.navCtrl.push(WelcomePage, {
          username: this.username,
          password: this.pwd
        });
        form.reset();
    // }
  }
  register(){
    console.log('REgister clicked');
  }
