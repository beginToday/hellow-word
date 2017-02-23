# hellow-word
this is first project


goBuy:function(event){
				if(this.main.is_free === 1){
					if($('.go-pay').text() == '立即购买'){
						this.isBuy = true;
					}
				}else if(this.main.is_free === 0){ //付费 跳转app

				}
			}
