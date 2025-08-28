# End-striyel-Elektronik-ve-Robotik-Gelistirme-ve-Uyum-Dersi-5--DEV-C++
##  //Metinsel ifadeler için arrayler
      
### sizeof() dizinin kaç karakterli olduğu

  #include <iostream>
  
    
    using namespace std;
    
    int main(int argc, char** argv) {
       //Metinsel ifadeler için arrayler
        
        string sehirler[] = {"Mardin","Malatya","Istanbul","Ankara","Adiyaman","Izmır"};
        //                    0        1          2          3        4
        //dry - dont't repeat yourself
        cout<<sehirler[0]<<endl;
        cout<<sehirler[1]<<endl;
        cout<<sehirler[2]<<endl;
        cout<<sehirler[3]<<endl;
        cout<<sehirler[4]<<endl;
        
        // 1 ile 5 arasındaki tüm sayıları ekren çıktısı olarak gösteriniz
        
        /* for(int i =1; i<=5;i++){
        
        cout<<i<<endl;
                 
        }
        
        //1 den1000 e kadar 2'şer 2'şer yazdır.
        
        for (int a= 5; a<=100; a+=2)
        cout<<a<<endl;   
    } */
     //5 ile 100 arasındaki çift sayılar
     for(int i = 5; i<=100;i++){
             
    
        if(i % 2==0){
        cout<<"CIFT SAYI:"<<i<<endl;
        }  else{
                cout<<"Tek sayi:"<<i<<endl;
        }
    }   
        /*
        for(int i = 100;i>=0;i-- ){
                
                
                
                }
                
                
    */
    int len = sizeof(sehirler) / sizeof(sehirler[0]);
    //sizeof(dizi) : dizinin bayt cinsinden boyutu
    cout<<"sehirler dizisi kac elelmalıdır :"<<len<<endl;
   
    //for döngüsü
    for (int i =0; i<sizeof(sehirler);i++){
    	cout<<sehirler[i]<<endl;
	}
	
	//foreach
	int numbers[] = {1,3,5,2,1,6,98};
	
	for(int sayi : numbers){
		cout<<sayi<<endl;
	}
	
	
	cout<<"sehirler"<<endl;
	for(string sehir : sehirler){
		cout<<sehir<<endl;
	}
    }




----------------------------------------------------------------------------------
## //Kullanıcıdan adet ürün adı ve fiyatlarını ve adet sayısı  alarak %20 kdv li ücretlerini ekran çıktısı olarak gösteren kodları yazınız.


