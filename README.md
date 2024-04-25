# formelsammlung
### Bewegungsgleichungen:


##### Gleichförmige Bewegung:
1. $a = 0$
2. $s = v \cdot t$

##### Gleichförmig beschleunigte Bewegung:
1. $a = konst$
2. $v_1 = v_0 + a \cdot t$
3. $s = \frac{1}{2} a t²$
4. $v = \sqrt{(v_0² +) \ \ 2as}$ aus 2. und 3.

##### Kreisbewegung:
- $\vec F_z = \frac{m \cdot v²}{r}$
- mit $v = \omega \cdot r$

### Beliebiges:

- $W_{pot} = m \cdot g \cdot h$
- $W_{kin} = \frac{1}{2}m \cdot v²$

- $S = \frac{\Delta W}{T}$ für Entropie mit Temperatur T in Kelvin

- Induktiv: Fall-spezifische Beobachtungen in allgemeine Schlussfolgerungen
- Deduktiv: Allgemeine Prinzipien auf spezifischen Fall anwenden und experimentell überprüfen

### DGL
###### DGL für mechanische Schwingung:
- $\vec F = m \cdot a \ \Leftrightarrow \ a = \frac{\vec F}{m}$ mit $\vec F_{Rück} = -D \cdot s(t)$ und $a(t) = \ddot s(t)$
- daraus: $\ddot s(t) = - \frac{D}{m} \cdot s(t)$ als *DGL*
- daraus => $s(t)$ vermuten als $s(t) = \hat s \cdot sin(\omega \cdot t)$
- $s(t)$ zweimal ableiten für $\ddot s(t) = a(t) = -\omega² \cdot \hat s \cdot sin(\omega \cdot t)$
- Einsetzen in *DGL* und doppeltes streichen
- $\omega² = \frac{D}{m}$ mit $T = 2\pi \frac{1}{\omega}$
  => $T = 2\pi \sqrt {\frac{m}{D}}$

###### DGL für Schwingkreise:
- $U_L + U_C = 0$ im elektromagnetischen Schwingkreis
- aus $U_L = -L \cdot \dot I(t)$ und $U_C = \frac{Q(t)}{C}$ ergibt sich:
- $\frac{Q(t)}{C} - L \cdot \dot I(t) = 0$  mit  $\dot I(t) = -\ddot Q(t)$
- daraus:
- $Q(t) = -LC \cdot \ddot Q(t)$

- $Q(t) = \hat Q \cdot cos(\omega \cdot t)$
  $\Leftrightarrow \ddot Q(t) =  -\omega² \cdot \hat Q \cdot cos(\omega \cdot t)$
- In DGL also
- $\hat Q \cdot cos(\omega \cdot t) = -LC \cdot -\omega² \cdot \hat Q \cdot cos(\omega \cdot t)$
  $\Leftrightarrow 1 = -LC \cdot -\omega²$
  $\Leftrightarrow -\frac{1}{LC} = -\omega²$
  $\Leftrightarrow \frac{1}{\sqrt{LC}} = \omega$

### Mechanische Schwingungen:
- $\vec F_G = -\vec F_{R0}$
Ruhelage:
- $\vec F_R = \vec F_G - \vec F_{0R} = 0$
Davor:
- $\vec F_R = \vec F_G + \vec F_1 = \vec F_G + \vec F_{0R} - D \cdot s = 0 - D \cdot s = -D \cdot s$ < 0
Danach:
- $\vec F_R = F_G + F_1 = F_G + F_{0R} - D \cdot s = 0 - D \cdot s = -D \cdot s$ > 0

- Harmonische Schwingung wenn $\vec F_R$ ~ s


- $T = 2\pi\sqrt{\frac{m}{D}}$ für ein Masse-Feder-Pendel
- $\omega = \frac{\varphi}{t} = \frac{2\pi}{T} = 2\pi f$
- $s(t) = \hat{s} \cdot sin(\omega \cdot t)$ für eine harmonische Schwingung
- $v(t) = \omega \cdot \hat{s} \cdot cos(\omega \cdot t)$ mit $\hat{v} = \omega \cdot \hat{s}$
- $a(t) = - \omega² \cdot \hat{s} \cdot sin(\omega \cdot t)$ mit $\hat{a} = \omega² \cdot \hat{s}$
- $D = \frac{m \cdot g}{l}$ für kleine winkel im Fadenpendel
- $T = 2\pi \sqrt{\frac{l}{g}}$ für kleine Winkel im Fadenpendel
- $D_{ges} = D_1 + D_2$ im horizontalen Federschwinger
- $D = 2 \cdot \rho \cdot g \cdot A$ im U-Rohr
- $W_{ges} = \hat W_{Elong} = \hat W_{Kin} = W_{Elong} + W_{Kin} = \frac{1}{2} D \cdot s² + \frac{1}{2} m \cdot v² =  konstant$

### Mechanische Wellen:
- $c = \lambda \cdot f$

- $l = n \cdot \frac{\lambda}{2}$ für stehende Wellen Eigenschwingung mit zwei gleichen Enden
- $f_n = n \cdot \frac{c}{\lambda_1} = n \cdot \frac{c}{2l}$ mit $n \in 1;2;3$ als Grundfrequenzen mit zwei gleichen Enden
- $l = (2n+1) \cdot \frac{\lambda}{4}$ mit $n \in 0;1;2;..$  für Resonanz mit zwei unterschiedlichen Enden

- $s(x; t) = \hat s \cdot sin(2\pi \cdot (\frac{t}{T} - \frac{x}{\lambda}))$ ist die allgemeine Wellengleichung
  -> aus der Schwingungsgleichung, "$t = (t - \Delta t) = (t - \frac{x_p}{c})$" und "$\omega = \frac{2\pi}{T}$" plus "$c = \frac{\lambda}{T}$"
- Reflexion am losen Ende: Kein Phasensprung
- Reflexion am festen Ende: Phasensprung (Berg<->Tal)
- $\frac{\Delta \varphi}{2 \pi} = \frac{\delta}{\lambda}$ als Zusammenhang von $\delta$ und $\Delta \varphi$ bei Interferenz von identischen Wellen.

### Elektromagnetische Wellen:
- $T = 2 \pi \sqrt{L \cdot C}$ für einen EM-Schwingkreis mit langer Spule
- $W_{mag} = \frac{1}{2} \cdot L \cdot I²(t)$
- $W_{el} = \frac{1}{2} \cdot C \cdot U²$
- $W_{ges} = \frac{1}{2} \cdot  C \cdot \hat U² = \frac{1}{2} \cdot L \cdot \hat I²$
- $U(t)$ und $I(t)$ haben $\Delta \varphi = \frac{\pi}{2}$
- Ein bewegtes Magnetfeld erzeugt ein E-Feld mit $E = \frac{U_{ind}}{d} = \frac{B \cdot d \cdot v}{d} = B \cdot v$
  -> Die beiden sind in Phase und breiten sich zusammen mit v (Lichtgeschwindigkeit) aus. Dabei stehen sie aber orthogonal zueinander.
  -> Auch bewegte E-Felder erzeugen B-Felder
- Ein leitender Stab kann mit $\lambda_k = \frac{2 \cdot l}{k}$ zu Resonanzschwingungen mit den Frequenzen $f_K = \frac{k \cdot c}{2 \cdot l}$ angeregt werden.
- $C_{Materie} \approx \frac{c_0}{\sqrt \varepsilon_0} < c_0$ in Materie
- Ihre Energie fällt ab mit $W \thicksim \frac{1}{r³}$

### Induktion:
- $U_{ind} = B \cdot v \cdot d$  da  $\vec F_{el} = \vec F_{L}$
- $U_{ind}(t) = -n \cdot \dot \phi(t)$ mit  $\dot \phi = A_S \cdot \dot B(t)$ oder $\dot \phi = B \cdot \dot A_S(t)$
- dabei kann statt $\dot B / \dot A_S$ auch $\frac{\Delta B}{\Delta t}$ oder $\frac{\Delta A_S}{\Delta t}$ genutzt werden für mittleres
- Flächenänderung durch rotation: $A_S = A \cdot cos(\varphi)$
- Bei schwingender Feldstärke oder Fläche:
  -> $U(t) = \hat U \cdot sin(\omega \cdot t)$  mit  $\hat U = n \cdot B \cdot A \cdot \omega$
  -> Bsp: Da $U_{ind}(t) = -n \cdot B \cdot \dot A(t)$  mit schwingendem $A(t) = A_0 \cdot sin(\omega \cdot t + \varphi_0)$
  Also $\dot A(t)$ entspricht der Ableitung $\dot A(t) = A_0 \cdot \omega \cdot cos(\omega \cdot t + \varphi_0)$
  und damit $U_{ind}(t) = -n \cdot B \cdot A_0 \cdot \omega \cdot cos(\omega \cdot t + \varphi_0)$
- Selbes Prinzip auch mit sinusförmiger $B(t)$ Änderung

- Selbstinduktion:
- $B = \mu_0 \cdot \mu_R \cdot \frac{n \cdot I}{l}$
- $\phi = B \cdot A = \frac{\mu_0 \cdot \mu_R \cdot n \cdot A \cdot I}{l}$
- $U_{ind} = -n \cdot \phi(t) = -\mu_0 \cdot \mu_R \cdot \frac{n² \cdot A}{l} \cdot \hat I(t)$
- mit $L = \mu_0 \ \mu_R \cdot \frac{n² \cdot A}{l}$ => $U_{ind} =  -L \cdot \dot I(t)$
- $Q = C \cdot U$

- Anschalten:
- $\dot I = \frac{U_0 - R \cdot I(t)}{L}$

- Ausschalten:
- $\dot I = -\frac{R_{ges} \cdot I(t)}{L}$

- $W_{mag} = \frac{1}{2} L \cdot I²$ als Energie eines Feldes
- $\rho_{mag} = \frac{B²}{V} = \frac{B²}{2 \ \mu_0 \ \mu_r}$ für Energiedichte
- $W = mc²$
- $p = m \cdot v$ für Impuls

### Wellenoptik

- **400 nm** = Blau
- **800 nm** = Rot

- *Kohärent* = gleiche Frequenz; konstante Phasendifferenz
- $\varphi = 2\pi \cdot \frac{d}{\lambda}$ als Zeiger position für einen Abstand d zur Quelle
  -> Für Phasenunterschied von zwei Zeigen also: $\Delta \varphi = 2\pi \cdot \frac{d_1 - d_2}{\lambda} = 2\pi \cdot \frac{\delta}{\lambda}$

- *Huygens-Prinzip*: Jede Stelle der Wellenfront kann als Ausgangspunkt einer Elementarwelle aufgefasst werden

###### Doppelspalt:
$d = Schirmmitten-Abst; g = Loch-Abst; a = Schirm-Abst$
- $\delta = k \cdot \lambda$ für das $k$-te maximum
- $\delta = (2k +1)\cdot \frac{\lambda}{2}$ für das $k$-te minimum

- $tan(\alpha_k) = \frac{d}{a}$
- $sin(\alpha_k) = \frac{\delta}{g}$ (bei Kleinwinkelnäherung)
  => $\frac{d}{a} = \frac{\delta}{g}$

- $k \leq \frac{g}{\lambda}$ für das größte mögliche Maxima
- Intensität $I$ ~ $s²$

###### Gitter:
- $\Delta \varphi = \frac{2\pi}{g}$ für einen Vollkreis $\Rightarrow$ größer $g$ $\rightarrow$ Max näher an neben-min
- $sin(\alpha_k) = k \cdot \frac{\lambda}{g}$ für das k-te Maximum mit
- $\delta = k \cdot \lambda$ für maxima
- $k \leq \frac{g}{\lambda}$ für das größte mögliche Maxima

- Nebenmaxima haben $(\frac{1}{n_{Spalte}})²$ Intensität der Hauptmaxima
- Anzahl Nebenmaxima: Spalte - 2
- Anzahl Nebenminima: Spalte - 1

- Mehr Spalte => Hellere, schärfere, kleinere Maxima
- Engere Spalte => Mehr, weiter entfernte Maxima

###### Einzelspalt:
- $sin(\alpha_k) = \frac{k \cdot \lambda}{b}$
- $k < \frac{b}{\lambda}$
###### Brechung:
- $\frac{sin(\alpha)}{sin(\beta)} = \frac{c_1}{c_2} = \frac{\lambda_1}{\lambda_2} = n$ (Brechungsgesetz)
- Stoff mit kleinerem c heißt optisch dichter
- Winkel am Lot gemessen
- $\alpha = 0 \Rightarrow \beta = 0$
- Optische Weglänge $L = n \cdot d$
- Bei Oberflächen Reflexion Erfolgt ein Maxima wenn Bragg-Bedingung
  $\frac{k \cdot \lambda}{2\cdot d} = sin(\varphi)$ => Glanz-winkel
###### Reflexion:
- $\alpha = \beta$
- Fall Optisch dichter zu dünner: $\beta > \alpha$
- Zu $\beta = 90°$ gehörender Winkel ist **Grenzwinkel** $\alpha_G$
  -> Hier: $sin(\alpha_G) = n$

###### Michelson-Interferometer:
- $k \cdot \frac{\lambda}{2} = \Delta s$

### Quantenphysik
###### Photoeffekt:
- Mit UV-Licht absorbierender Glasplatte: Kein Photoeffekt
  => Photoeffekt *abhängig von Frequenz* nicht Intensität
- bei der **Gegenfeld-Methode** wird entgegen gerichtete Spannung angelegt. Fällt die gesamt-Spannung auf null gilt: $W_{kin} = W_{El} = e \cdot U$ für die Energie der *schnellsten Elektronen*
- Photonen besitzen die Energie $W_{ph} = h \cdot f$
- $W_{kin} = h \cdot f - W_{A}$ für die Kinetische Energie nach dem Aufprall
  => Daraus ergibt sich eine Ursprungs-Gerade, deren $y_0 = -W_A$
- $h$ = Planck-Konstante
- Wichtig!! Zum rechnen $eV$ in $J$ umrechnen, dafür einfach $\cdot\ e$
- Nach der Relativitätstheorie haben sie Masse und Impuls $\lambda  = \frac{h}{p}$

###### Interferenz:
- Einzelne Photonen weisen Interferenzmuster auf. Sie interferieren mit sich selbst.
- Das Zeiger-Model kann mit Wahrscheinlichkeit-Amplituden und $\psi-Zeigern$ genutzt werden
- Die Auftreffwahrscheinlichtkeit(Intensität) ist also $|\psi|²$

###### Eigenschaften:
- Nicht-Lokalität
- Interferenz-Verhalten
- Eindeutigkeit bei Messung
- Statistisches Verhalten
- Komplementaritätsprinzip (Wellen oder Teilchen-verhalten, nie beides)

###### Elektronenbeugung:
- **De Broglie** Wellenlänge
- $\lambda_B = \frac{h}{p}$
- $W_{\psi} = h \cdot f$

###### Unbestimmtheitsrelation:
- $sin(\alpha) = \frac{\Delta p_x}{p}$
- $sin(\alpha) = \frac{h}{p \cdot \Delta x}$
  $\Rightarrow \Delta x \cdot \Delta p_x \geq h$
- Man kann nie $x$ und $p$ gleichzeitig genau messen
