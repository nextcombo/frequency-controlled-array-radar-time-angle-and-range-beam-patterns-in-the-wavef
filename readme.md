# Frequency-Controlled Array Radar Time, Angle, and Range Beam Patterns in the Wavefront Domain [with MATLAB Code]

MATLABCode%% Uniform Linear (ULA) Frequency-Controlled Array (FDA) Beam Pattern\nclc;clear ;close;\n​\n​\n%% ------Uniform Linear FDA Radar Parameter Settings\nj=sqrt(-1);\nM=12; %Number of emitting elements\nf0=2e9; %Carrier center frequency\ndelta_f=3000; % Frequency offset between adjacent elements\nc=3e8;        %Light Speed\nlamda=c/f0;  % Wavelength\nd=lamda/2;    %Element spacing\nRu=c/delta_f;  %Maximum Unblurred Distance\ntheta=(-90:1:90)*pi/180; % Measure the angle vector\nR=linspace(0,3e5,1000); %Measure the distance vector\nf=f0+(0:M-1)*delta_f; %Array of Elementary Frequency Vectors (uniformly increasing)\nR0 = 1e5;\ntheta0 = 30/180*pi;  %% The angle and distance of the antenna pointing to the target\nt=Ru/c; % Period of time between the dimension and the time\nT=linspace(0,2*t,500);\nDelta_f=(0:M-1)*delta_f;\nD=d*(0:M-1);\n​\n% -----FDA Beam Pattern\nP1 = zeros(length(theta),length(R)); % Beam pattern\nSimulation results  

## Images

![(Frequency-Controlled Array)Frequency-Controlled Array Radar Time, Angle, and Range Beam Directional Patterns [with MATLAB Code]](01.jpg)
![(Frequency-Controlled Array)Frequency-Controlled Array Radar Time, Angle, and Range Beam Directional Patterns [with MATLAB Code]](02.jpg)
![(Frequency-Controlled Array)Frequency-Controlled Array Radar Time, Angle, and Range Beam Directional Patterns [with MATLAB Code]](03.jpg)
![(Frequency-Controlled Array)Frequency-Controlled Array Radar Time, Angle, and Range Beam Directional Patterns [with MATLAB Code]](04.jpg)
![(Frequency-Controlled Array)Frequency-Controlled Array Radar Time, Angle, and Range Beam Directional Patterns [with MATLAB Code]](05.jpg)
![(Frequency-Controlled Array)Frequency-Controlled Array Radar Time, Angle, and Range Beam Directional Patterns [with MATLAB Code]](06.jpg)
![(Frequency-Controlled Array)Frequency-Controlled Array Radar Time, Angle, and Range Beam Directional Patterns [with MATLAB Code]](07.jpg)
![(Frequency-Controlled Array)Frequency-Controlled Array Radar Time, Angle, and Range Beam Directional Patterns [with MATLAB Code]](08.jpg)
![(Frequency-Controlled Array)Frequency-Controlled Array Radar Time, Angle, and Range Beam Directional Patterns [with MATLAB Code]](09.jpg)
![(Frequency-Controlled Array)Frequency-Controlled Array Radar Time, Angle, and Range Beam Directional Patterns [with MATLAB Code]](10.jpg)
![(Frequency-Controlled Array)Frequency-Controlled Array Radar Time, Angle, and Range Beam Directional Patterns [with MATLAB Code]](11.jpg)
![(Frequency-Controlled Array)Frequency-Controlled Array Radar Time, Angle, and Range Beam Directional Patterns [with MATLAB Code]](12.jpg)
![(Frequency-Controlled Array)Frequency-Controlled Array Radar Time, Angle, and Range Beam Directional Patterns [with MATLAB Code]](13.jpg)
![(Frequency-Controlled Array)Frequency-Controlled Array Radar Time, Angle, and Range Beam Directional Patterns [with MATLAB Code]](14.jpg)
![(Frequency-Controlled Array)Frequency-Controlled Array Radar Time, Angle, and Range Beam Directional Patterns [with MATLAB Code]](15.jpg)
![(Frequency-Controlled Array)Frequency-Controlled Array Radar Time, Angle, and Range Beam Directional Patterns [with MATLAB Code]](16.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
