# End-striyel-Elektronik-ve-Robotik-Gelistirme-ve-Uyum-Dersi-5--DEV-C++
##  //Metinsel ifadeler için arrayler
        #include <iostream>
    
    using namespace std;
    
    int main(int argc, char** argv) {
       //Metinsel ifadeler için arrayler
        
        string sehirler[] = {"Mardin","Malatya","Istanbul","Ankara","Adiyaman"};
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
        cout<<"CİFT SAYI:"<<i<<endl;
        }  else{
                cout<<"Tek sayi:"<<i<<endl;
        }
    }   
        
        for(int i = 100;i>=0;i-- ){
                
                
                
                }
    }


