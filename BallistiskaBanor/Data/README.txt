Vi antar att räckvidden inte är vart den landar (!)

Utan luftmotstånd/coriolis
	max för H = 0:
		x = 30835.8807
		theta = 45
	max för H = 300:
		x = 31134.2809
		theta = 44.7
Med luftmotstånd
	max för H = 300:
		x = 16017.4816
		theta = 33.9
	max för D = 1.5 * 0.001:
		x = 12665.9145
		theta = 30.0
		
Luftmotstånd/coriolis:
	max för a = 0, lambda = 56:
		z = -5569.8639
	max för a = 90, lambda = 56:
		z = -5597.952
	max för a = 0, lambda = 0:
		z = -5607.3826
	max för a = 0, lambda = 56:
		z = -5657.3943


x	y	z
wx	wy	wz
vx	vy	0

wz*vx*y + wx*vy*z - wz*vy*x - wy*vx*z

(-2*50*360*Omega/(2*PI))*(COS(Lambda)*550*SIN(.MODEL_1.ThetaAngle))
(-2*50*360*Omega/(2*PI))*(COS(Lambda)*550*COS(.MODEL_1.ThetaAngle))
(-2*50*360*Omega/(2*PI))*(SIN(Alpha)*COS(Lambda)*550*SIN(.MODEL_1.ThetaAngle) - SIN(Lambda)*550*COS(.MODEL_1.ThetaAngle))

x	y	z
0	wy	wz
vx	vy	vz

wy*vz*x + wz*vx*y - wz*vy*x - wy*vx*z