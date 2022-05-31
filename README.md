# workshop-nii


```{R Basics}
hello <- function(){
  print('Hello World')
}


 > my_fav_variable
Error: object 'my_fav_variable' not found
> my_fav_variable <- c('IL6','LINC','OAS1')
> my_fav_variable
[1] "IL6"  "LINC" "OAS1"
> #Its working fine


#composition of dataframe with one charector vector and one numeric vector
 names<-c('jb','varun','anshul')
> hight<-c('5.5','5.7','6')
> index<-data.frame(names,hight)
> index
   names hight
1     jb   5.5
2  varun   5.7
3 anshul     6
> rbind(index,new=c('athar',5.9))
   names hight
1     jb   5.5
2  varun   5.7
3 anshul     6
4  athar   5.9
> index<-rbind(index,new=c('athar',5.9))
> index
   names hight
1     jb   5.5
2  varun   5.7
3 anshul     6
4  athar   5.9
> cbind(index,lab=c('moil','sfbl','lii','iil'))
   names hight  lab
1     jb   5.5 moil
2  varun   5.7 sfbl
3 anshul     6  lii
4  athar   5.9  iil
> index<-cbind(index,lab=c('moil','sfbl','lii','iil'))
> index
   names hight  lab
1     jb   5.5 moil
2  varun   5.7 sfbl
3 anshul     6  lii
4  athar   5.9  iil
> 

```
