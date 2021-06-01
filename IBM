#include <iostream>
using namespace std;
 

    // BMI rechnen .
 double ibm_rechnen(double  Gross , double Gewicht ){
        double b=(Gewicht/((Gross/100)*(Gross/100)) );
        return b;
}



int main(){
    // Varieble.
    string name;
    string  geschlecht ;
    int age;
    double fun_result;
    double Gross;
    double Gewicht;
    double ibm_rest;
    //string keyword_F ="Feminie";
    //string keyword_f ="feminie";


 // info eingeben .
 cout <<"--Enter bitte Ihre Name: " ;
 cin>>name;
 cout <<"--Enter geschlecht:Male/Feminie: ";
 cin>>geschlecht;
 cout << "--Enter Ihre Alte: " ;
 cin >> age;
cout<<"--Enter ihre Grosse: ";
cin>>Gross;
cout<<"--Enter Ihre Gewicht";
cin>>Gewicht;

    // 
    //size_t result_k_F =  geschlecht.find(keyword_F);
    //size_t result_k_f =  geschlecht.find(keyword_f);
    // varieble um eine wort in string zu suchen diefinert .
    size_t FirstResult_F = geschlecht.find("Feminie");
    size_t SecandResult_f = geschlecht.find("feminie");
    size_t TherethResult_M = geschlecht.find("Male");
    size_t FourthResult_m = geschlecht.find("male");

    
    
    fun_result=ibm_rechnen(Gross,Gewicht);
    cout<<"Ergibniss"<<fun_result<<endl;



        if (FirstResult_F == string::npos or SecandResult_f == string::npos )   {      // (geschlecht[0] ==  "M" or geschlecht[0] == "m"){      // OR    if(geschlecht.length()=4)
       if (age >19 & age <=24){
        if(fun_result<19){
           ibm_rest= fun_result - 19 ;
            cout << ibm_rest<< "Untergewicht "<<endl;
        }else if(fun_result>=19 & fun_result<=24){
            cout<<"Normalgewicht"<<endl;
        } else if(fun_result>24 ){
            ibm_rest =   fun_result -24;
            cout << ibm_rest <<"Ubergewicht"<<endl;
        }   }  else if(age >25 & age < 35){
            if(fun_result<20){
           ibm_rest= fun_result - 20 ;
            cout << ibm_rest<< "Untergewicht "<<endl;
        }else if(fun_result>=20 & fun_result<=25){
            cout<<"Normalgewicht"<<endl;
        } else if(fun_result>25 ){
            ibm_rest =   fun_result - 25;
            cout << ibm_rest <<"Ubergewicht"<<endl;
        }  } else if(age >35 & age <44 ){
            if(fun_result<21){
           ibm_rest= fun_result - 21 ;
            cout << ibm_rest<< "Untergewicht "<<endl;
        }else if(fun_result>=21 & fun_result<=26){
            cout<<"Normalgewicht"<<endl;
        } else if(fun_result>26 ){
            ibm_rest =   fun_result - 26;
            cout << ibm_rest <<"Ubergewicht"<<endl;
        }  }else if(age >45 & age <54){
            if(fun_result<22){
           ibm_rest= fun_result - 22 ;
            cout << ibm_rest<< "Untergewicht "<<endl;
        }else if(fun_result>=22 & fun_result<=27){
            cout<<"Normalgewicht"<<endl;
        } else if(fun_result>27 ){
            ibm_rest = fun_result-27;
            cout << ibm_rest <<"Ubergewicht"<<endl;
        }  }else if (age >55 & age < 64){
            if(fun_result<23){
           ibm_rest= fun_result - 23 ;
            cout << ibm_rest<< "Untergewicht "<<endl;
        }else if(fun_result>=23 & fun_result<=28){
            cout<<"Normalgewicht"<<endl;
        } else if(fun_result>28 ){
            ibm_rest = fun_result - 28;
            cout << ibm_rest <<"Ubergewicht"<<endl;
        }  }if (age > 65){
            if(fun_result<24){
           ibm_rest= fun_result - 24 ;
            cout << ibm_rest<< "Untergewicht "<<endl;
        }else if(fun_result>=24 & fun_result<=29){
            cout<<"Normalgewicht"<<endl;
        } else if(fun_result>29 ){
            ibm_rest =  fun_result -29;
            cout << ibm_rest <<"Ubergewicht"<<endl;
        }  }
     } 
        else if (TherethResult_M == string::npos or FourthResult_m == string::npos){                    // if(geschlecht.length()=7)
           if (age >19 & age <24){
        if(fun_result<19){
           ibm_rest= fun_result - 19 ;
            cout << ibm_rest<< "Untergewicht "<<endl;
        }else if(fun_result>=19 & fun_result<=24){
            cout<<"Normalgewicht"<<endl;
        } else if(fun_result>24 ){
            ibm_rest =  24 - fun_result;
            cout << ibm_rest <<"Ubergewicht"<<endl;
        }   }  else if(age >25 & age <=34){
            if(fun_result<20){
           ibm_rest= fun_result - 20 ;
            cout << ibm_rest<< "Untergewicht "<<endl;
        }else if(fun_result>=20 & fun_result<=25){
            cout<<"Normalgewicht"<<endl;
        } else if(fun_result>25 ){
            ibm_rest =  fun_result-25 ;
            cout << ibm_rest <<"Ubergewicht"<<endl;
        }  } else if(age >35 & age <44 ){
            if(fun_result<21){
           ibm_rest= fun_result - 21 ;
            cout << ibm_rest<< "Untergewicht "<<endl;
        } } else if(fun_result>=21 & fun_result<=26){
            cout<<"Normalgewicht"<<endl;
        } else if(fun_result>26 ){
            ibm_rest =  fun_result - 26;
            cout << ibm_rest <<"Ubergewicht"<<endl;
        }  }else if(age >45 & age <54){
            if(fun_result<22){
           ibm_rest= fun_result - 22 ;
            cout << ibm_rest<< "Untergewicht "<<endl;
        }else if(fun_result>=22 & fun_result<=27){
            cout<<"Normalgewicht"<<endl;
        } else if(fun_result>27 ){
            ibm_rest = fun_result - 27;
            cout << ibm_rest <<"Ubergewicht"<<endl;
        }  }else if (age >55 & age < 64){
            if(fun_result<23){
           ibm_rest= fun_result - 23 ;
            cout << ibm_rest<< "Untergewicht "<<endl;
        }else if(fun_result>=23 & fun_result<=28){
            cout<<"Normalgewicht"<<endl;
        } else if(fun_result>28 ){
            ibm_rest = fun_result -28 ;
            cout << ibm_rest <<"Ubergewicht"<<endl;
        }  if (age > 65){
            if(fun_result<24){
           ibm_rest= fun_result - 24 ;
            cout << ibm_rest<< "Untergewicht "<<endl;
        }else if(fun_result>=24 & fun_result<=29){
            cout << "Normalgewicht"<<endl;
        } else if(fun_result>29 ){
            ibm_rest =  fun_result-29;
            cout << ibm_rest <<"Ubergewicht"<<endl;
        }  }
        } else {
         cout<<"1-Erorr Information"<<endl;
         cout<<"1-please do it Agein"<<endl;
            }
      

    string begross;
    if (FirstResult_F == string::npos or SecandResult_f == string::npos ){

      begross ="Sehr geehrter Herr " ;
      }else if (TherethResult_M == string::npos or FourthResult_m == string::npos){
               begross  ="Sehr geehrte Frau ";
      }else{
          cout<<"2-Erorr Information"<<endl;
         cout<<"2-please do it Agein"<<endl;
            }
      
    
    cout<< begross <<name<<" Das ist die Ergibniss ihre Untersuchung "<<endl;









    return 0;

}
