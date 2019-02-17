# hello-world
create something

x=[0 0.5 1 -0.5 0];
y=fftshift(fft(x,50));
f=(-24:25)*5/length(y);
stem(f,abs(y));
t=-10*pi:10*pi;
x1=sin(2*pi*10*t)+cos(2*pi*10*t);
disp(size(x1));
