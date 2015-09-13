## Dot product

### Basics

- Definition: \(\vec{a} . \vec{b} = (a_1 b_1, a_1 b_2, ..., a_n b_n)\)
- Geometric: \(\vec{a} . \vec{b} = ||\vec{a}|| ||\vec{b}|| cos \theta\) where \(\theta\) is angle between vectors
- Orthogonal: \(\theta = 90 => cos(90) = 0 => \vec{a}.\vec{b} = 0\)
- Codirectional: \(\theta = 0 => cos(0) = 1 => \vec{a} . \vec{b} = ||\vec{a}|| ||\vec{b}||\)
- Self dot: \(\vec{a} . \vec{a} = ||\vec{a}||^{2}\)
- Length: \(||\vec{a}|| = \sqrt{\vec{a} . \vec{a}}\)

### Unit vectors

- Scale vector's magnitude to 1 to get unit vector \(\hat{a} = \frac{\vec{a}}{||\vec{a}||}\)
- \(\vec{a} = \hat{a} \iff ||\vec{a}||=1\)

### Cauchy-Schwartz inequality

Definition: 
- Length of the sum of two vectors is less than or equal to the sum of the lengths of the vectors
- \(|\vec{a} . \vec{b}| \leq ||\vec{a}|| . ||\vec{b}\)
- \(|vec{a} . \vec{b}| = ||\vec{a}|| . ||\vec{b}|| \iff \vec{a} = c\vec{b}\) i.e. collinear

Proof:

- Expand: \(|a_0 b_0 + a_1 b_1 + ... + a_n b_n | \leq \sqrt{a^2_0 + a^2_1 + ... + a^2_n}\sqrt{b^2_0 + b^2_1 + ... b^2_n}\)
- Therefore: \(|a+b|^2 = (a+b) . (b+a) = a.a + b.b + 2a.b = (|a| + |b|)^2\)
- \(|a|^2 + |b|^2 + 2a.b \leq |a|^2 + |b|^2 + 2|a||b| = (|a| + |b|)^2\)
- \(|a+b|^2 \leq (|a|+|b|)^2\) or \(|a+b| \leq |a| + |b|\).

### Triangle inequality

- Definition: \(||\vec{a} + \vec{b}|| \leq ||\vec{a}||||\vec{b}||\)
- Proof:

  
  
  