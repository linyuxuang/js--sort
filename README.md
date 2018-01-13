# js--sort
js-sort（排序）

                    var arr=[1,2,56,78,9,0];
                      arr.sort(function(a,b){
                      return a-b;
                    })
                         console.log(arr)    //  [0, 1, 2, 9, 56, 78]



                      var arr=[1,2,56,78,9,0];
                        arr.sort(function(a,b){
                        return b-a;
                    })
                       console.log(arr)    //[78, 56, 9, 2, 1, 0]

         

                       function paixun(texts){
                        return function(vals1,vals2){
                        var v1=vals1[texts];
                        var v2=vals2[texts];
                         if(v1<v2){
                           return -1;
                          }else if(v1>v2){
                             return 1;
                          }else{
                            return 0;
                          }
                         }
                       }

                    var data=[{name:"zhangsan",age:102},{name:'a0000000lisi',age:903}];
                         data.sort(paixun("age"));
                          console.log(data[0].name);   //zhangsan

                         data.sort(paixun("name"));
                           console.log(data[0].name);   //lisi
                          
       
       
                    var array=[1,4,5,2,3]
                      var ds= array.sort(function(n1,n2){
                        if(n1<n2){
                          return -1;
                        }else if(n1>n2){
                          return 1;
                        }else{
                          return 0;
                        }
                       })
                      console.log(ds)   //    [1, 2, 3, 4, 5]

       
       
       
       
       
       
       
       
