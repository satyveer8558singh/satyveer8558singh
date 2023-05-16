newton second law
program newton_law
implicit none
  real::f,m,a
  write(*,*)"calculate force by using newton 2nd law "
  write(*,*)"mass:"
 read(*,*)m
write(*,*)"Acceleration:"
 read(*,*)a

     f=m*a
  print*,"calculate the value of force" ,f
end program newton_law
~                                                                                                         
