## [Spectral Irradiance](https://ch.mathworks.com/matlabcentral/fileexchange/52938-spectral-irradiance?s_tid=prof_contriblnk)

Figure about Spectral Irradiance using Matlab and Excel



### Functions

```matlab
%Spectral Irradiance by Montasir Mirghani%
%09.09.2015
%Data from Exel - http://rredc.nrel.gov/solar/spectra/am1.5/
spectrum=xlsread('SpectrumAM');
x=spectrum(:,1);
y1=spectrum(:,2);
y2=spectrum(:,3);
y3=spectrum(:,4);
plot(x,y1,x,y2,x,y3);
xlabel('Wavelenth nm');
ylabel('Spectral Irradiance W m^{-2} nm^{-1}');
legend('AM0 (ASTM G-173-03)',...
    'AM1.5 Global (ASTM G-173-03)',...
    'AM1.5 Direct (ASTM G-173-03)');
```



### Links

[Spectral Irradiance - MathWorks](https://ch.mathworks.com/matlabcentral/fileexchange/52938-spectral-irradiance?s_tid=prof_contriblnk)

[Author Profile - MathWorks](https://ch.mathworks.com/matlabcentral/profile/authors/5200624-montasir-mirghani)