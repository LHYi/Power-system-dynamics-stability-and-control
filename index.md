# Questions

- [Questions](#questions)
  - [Lecture 1-2](#lecture-1-2)
  - [Lecture 3-4](#lecture-3-4)
  - [Lecture 5-6](#lecture-5-6)
  
## Lecture 1-2

Contributor: Hongyi, Chengqi

### 1. Why does generator operate at synchronous speed?

Because the AC grid is operating at a fix frequency.

### 2. Why do we need voltage control?

Voltage control is essential to maintain the reactive power in the system within the controllable region. Maintaining the voltage within the limits is also necessary for the insulation of the devices.

### 3. Which of voltage and frequency control can be influenced by the network?

Voltage control. To control the frequency, it requires the injection of the active power, which is not possible by changing the network.

### 4. How does one characterise lightening strikes in transmission line?

The peak value (usually in kiloampere) and the duration (typical value 1.2/50 microseconds).

### 5. How does one characterise switching transient in transmission system?

By the magnitude of the over voltage and the duration. (Typical value for 400 kV system, 2 times the rated voltage and 200~2000 microseconds)

### 6. What types of power plant exhibit mechanical resonance in the sub synchronous frequency range?

All power plants that utilize multi-state/pressure-compounded turbines.

### 7. What type of stability study is important for assessing the fault behaviour of synchronous generator?

Trasient stability. Transient stability problem usually arises when the output power of the generator drops, while subsynchronous resonance usually comes from network side, especially which is series compensated.

### 8. What is of prime importance in small signal stability studies? 

Dumping is a critical parameter in such studies.

# Lecture 3-4

Contributor: Hongyi

## Quesions

### 1. What are the functionsof closed circuit rotor windings?

In majority of the cases additional windings, known as damper winding, are included to produce damping effect. These windings are closed and their dissipative action produce damping to rotor oscillations.

### 2. Why should the synchronous reactance be so high (1.5 to 2.0 p.u.)?

The reactance is in reverse proportional to the reluctance. In the design of the generator, the reluctance is always low to optimize the generator in terms of material and size.

### 3. Why should X/R ratio of a generator be so high?

The reactance is very high, due to the reasons stated in Q2.

The register of the circuit is designed to be as low as possible, since the conductors are conducting thousands of amperes. In order to reduce the thermal loss, the resistance should be low, resulting in a high X/R ratio (typical value around 300).

### 4. Can the generator be operated at theoretical maximum power? Justify your answer

No. If the generator is operated at maximum power, i.e. &delta; =90&deg;, it is not stable. For example, if the mechanic torque increases, which will lead to the increase in &delta;, the electrical power output is supposed to increase as well to keep the system stable. However, if it is operating at maximum output, the ouput power will decrease, which will lead to a further increase of &delta; and the lost of synchronization.

# Lecture 5-6

Contributor: Hongyi

## Questions

### 1. Why do you think that real power can be produced by salient pole machine even there is no excitation?

It's due to the difference of the saliency, which leads to variable reluctance along the air gap. The amount of reluctance power may not be great but its main advantage lies in increasing the synchronising power and thereby improving the stability of the machine. It is worth noticing that the reluctance power changes the shape of P-&delta; curve. The maximum output power is higher and the slope in the steady operation area is larger, which implies that the stability of the generator in a transient process.

### 2. When do we use salient pole machines?

For low speed machines (usually found in hydro grnerators).

### 3. Why Xd is larger than Xq?

The air gap along the d-axis is smaller, which leads to smaller reluctance and larger reactance.

### 4. Why do we use Blondel's two reaction theory?

Because the air gap is not uniform so it cannot be modeled as a single reactance.

### 5. Is the reluctance power going to help with the stability or not?

It will help improve the stability. If the excitation is lost in both cylindrical and salient machines, the cylindrical one will accelerate faster since there will be no electrical power generated at all.

---
Most of the answers above comes from Abduljalil and Cameron during the lecture.
