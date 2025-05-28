# Sonorus Secret

**Description**: A picture may be worth a thousand words, but only Sonorus can reveal its secret sound.

**File**: [Chall.jpg](./Chall.jpg)

## Solution

### Step 1:- Using `Foremost` on the given challenge image<br>
### Command:
```
foremost -T Chall.jpg
```


![Using Foremost](../Sonorus%20Secret/imgs/Foremost_output.png)

### Step 2:- Analyzing the wav file in `AUDACITY`, the `Steganogram` reveals the flag.
<br>

![Analysis](../Sonorus%20Secret/imgs/WAV%20STEG%20MAGIC.png)
<br>
<br>
## Flag:
```
KJSSE_CTF{W4V_5T3G_M4G1C}
```