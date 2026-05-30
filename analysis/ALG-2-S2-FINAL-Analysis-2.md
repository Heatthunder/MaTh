# Complete Multi-Unit Diagnostic Analysis

---

## UNIT: TRIGONOMETRY

## Topic: Special Right Triangles – 45-45-90
- Core Mechanism: In a 45-45-90 triangle, both legs are equal and the hypotenuse equals $L\sqrt{2}$, producing the fixed ratio $L : L : L\sqrt{2}$ between the two legs and hypotenuse.
- The Common Operational Trap: Students apply $\sqrt{2}$ in the wrong direction — multiplying by $\sqrt{2}$ when the hypotenuse is the known quantity (requiring division), or they swap the $\sqrt{2}$ multiplier with the $\sqrt{3}$ multiplier from the 30-60-90 triangle.
- **The Golden Rule: If you know the leg $L$, multiply by $\sqrt{2}$ to get the hypotenuse: $H = L\sqrt{2}$; if you know the hypotenuse $H$, divide and rationalize to get the leg: $L = \frac{H}{\sqrt{2}} = \frac{H\sqrt{2}}{2}$.**

## Topic: Special Right Triangles – 30-60-90
- Core Mechanism: In a 30-60-90 triangle, the short leg (SL) is opposite $30°$, the long leg (LL) equals $\text{SL}\cdot\sqrt{3}$, and the hypotenuse equals $2\cdot\text{SL}$, giving the ratio $\text{SL} : \text{SL}\sqrt{3} : 2\,\text{SL}$.
- The Common Operational Trap: Students skip the short leg as an intermediate step and try to jump directly from the hypotenuse to the long leg; when given the long leg, they multiply by $\sqrt{3}$ to find the short leg instead of dividing, inverting the relationship $\text{SL} = \frac{\text{LL}}{\sqrt{3}}$.
- **The Golden Rule: Always isolate the short leg first — $\text{SL} = \frac{H}{2}$ when the hypotenuse is known, or $\text{SL} = \frac{\text{LL}}{\sqrt{3}}$ when the long leg is known — then build all other sides from SL.**

## Topic: Right Triangle Trigonometric Ratios (Finding Missing Sides)
- Core Mechanism: Given a reference angle and one known side, identify the positional relationship of the unknown side (opposite, adjacent, or hypotenuse) and apply the corresponding SOH CAH TOA ratio: $\sin\theta = \frac{\text{opp}}{\text{hyp}}$, $\cos\theta = \frac{\text{adj}}{\text{hyp}}$, $\tan\theta = \frac{\text{opp}}{\text{adj}}$.
- The Common Operational Trap: When $x$ appears in the denominator of the trig ratio (e.g., $\cos 25° = \frac{12}{x}$), students attempt to subtract or divide the trig value rather than cross-multiplying first, leaving $x$ incorrectly isolated or stranded in the denominator.
- **The Golden Rule: If $x$ is in the denominator, cross-multiply to get $x \cdot (\text{trig value}) = \text{known side}$, then divide both sides — $x = \frac{\text{known side}}{\text{trig value}}$; if $x$ is in the numerator, simply multiply the denominator by the trig value.**

## Topic: Inverse Trigonometric Functions (Finding Missing Angles)
- Core Mechanism: When two side lengths of a right triangle are known, use the inverse trig functions to recover the missing angle: $x = \sin^{-1}\!\left(\frac{\text{opp}}{\text{hyp}}\right)$, $x = \cos^{-1}\!\left(\frac{\text{adj}}{\text{hyp}}\right)$, or $x = \tan^{-1}\!\left(\frac{\text{opp}}{\text{adj}}\right)$, noting that $\sin^{-1} \neq \frac{1}{\sin}$.
- The Common Operational Trap: Students correctly identify the two known sides but select the wrong inverse function (e.g., applying $\cos^{-1}$ to an opposite-over-hypotenuse ratio), because they have not labeled opposite, adjacent, and hypotenuse relative to the specific angle being solved for.
- **The Golden Rule: Label all three sides as opposite, adjacent, and hypotenuse relative to the unknown angle $x$ first; then select the one inverse function (SOH→$\sin^{-1}$, CAH→$\cos^{-1}$, TOA→$\tan^{-1}$) whose ratio matches the two sides you were given.**

## Topic: Angles of Elevation and Depression
- Core Mechanism: The angle of elevation is measured upward from horizontal to the line of sight; the angle of depression is measured downward from horizontal to the line of sight; each defines a right triangle to which SOH CAH TOA is applied to find the missing side or angle.
- The Common Operational Trap: Students place the angle of depression inside the right triangle at the wrong vertex — measuring it from the vertical instead of from the horizontal — causing an incorrect trig ratio; they must recognize that the angle of depression is exterior to the triangle yet equal to the interior angle of elevation as alternate interior angles on parallel horizontal lines.
- **The Golden Rule: The angle of depression is always measured from the horizontal line looking downward and sits outside the right triangle; redraw the triangle clearly marking the correct interior angle (equal to the angle of depression) before applying SOH CAH TOA.**

## Topic: The Unit Circle
- Core Mechanism: On a unit circle (radius $= 1$), each angle $\theta$ corresponds to a coordinate point $(\cos\theta,\, \sin\theta)$; the first-quadrant coordinates for $30°$, $45°$, and $60°$ are derived from special right triangles and then extended to all four quadrants by applying the correct sign pattern for each quadrant.
- The Common Operational Trap: Students swap the coordinates for $30°$ and $60°$, writing $\cos 30° = \frac{1}{2}$ (which is actually $\sin 30°$) because they do not firmly associate the larger value $\frac{\sqrt{3}}{2}$ with the $x$-coordinate (cosine) at $30°$; they also misapply quadrant signs when rotating past $90°$.
- **The Golden Rule: At $30°$ the point is $\!\left(\frac{\sqrt{3}}{2},\frac{1}{2}\right)$—cosine is larger; at $60°$ the values swap to $\!\left(\frac{1}{2},\frac{\sqrt{3}}{2}\right)$—sine is larger; then multiply each coordinate by the appropriate $(\pm,\pm)$ sign of its quadrant to fill in all four quadrants.**

## Topic: Radian Measure and Conversion
- Core Mechanism: Degrees and radians measure the same angles on two different scales related by the identity $180° = \pi$ radians; multiply by the appropriate unit-canceling conversion factor to switch between them.
- The Common Operational Trap: Students multiply by the inverted factor — using $\frac{180°}{\pi}$ when converting from degrees to radians or $\frac{\pi}{180°}$ when converting from radians to degrees — producing a result in the wrong units that is neither simplified nor correct.
- **The Golden Rule: Degrees $\to$ radians: multiply by $\frac{\pi}{180°}$ and reduce the resulting fraction; radians $\to$ degrees: multiply by $\frac{180°}{\pi}$, cancel $\pi$, and simplify the arithmetic.**

---

## UNIT: COUNTING AND PROBABILITY

## Topic: Fundamental Counting Principle (FCP)
- Core Mechanism: When a task involves a sequence of independent decisions, the total number of possible outcomes equals the product of the number of valid options at each individual decision stage.
- The Common Operational Trap: Students add the number of options across stages instead of multiplying; when repetition is not allowed, they also fail to decrement the available options for each subsequent selection (using $15 \cdot 15 \cdot 15$ instead of $15 \cdot 14 \cdot 13$).
- **The Golden Rule: Draw one blank for every decision slot, fill in the exact number of valid options per slot based on any stated constraints (and reduce the count if no repetition is allowed), then multiply every blank together.**

## Topic: Permutations
- Core Mechanism: A permutation counts the number of ways to select and arrange $r$ items from $n$ distinct items where the specific order of those items matters, computed by $_{n}P_{r} = \frac{n!}{(n-r)!}$.
- The Common Operational Trap: Students use combinations instead of permutations for problems where individuals are assigned distinct ranked roles (president, VP, treasurer), treating the assignment as an unordered group because they fixate on the word "choose."
- **The Golden Rule: If the selected individuals occupy specific, distinguishable positions — meaning swapping two people creates a different, distinct outcome — it is a permutation; use $_{n}P_{r}$.**

## Topic: Combinations
- Core Mechanism: A combination counts the number of ways to select $r$ items from $n$ distinct items where the order of selection is irrelevant, computed by $_{n}C_{r} = \frac{n!}{(n-r)!\,r!}$.
- The Common Operational Trap: Students misidentify the problem as a permutation because words like "choose," "select," or "pick" appear, not recognizing that any rearrangement of the selected set produces the same committee, team, or group.
- **The Golden Rule: If the selected items form an undifferentiated subset — swapping two members still yields the same group with no structural difference — use combinations $_{n}C_{r}$.**

## Topic: Word Arrangements (Permutations with Repeated Elements)
- Core Mechanism: The number of distinct arrangements of an $n$-letter word where specific letters repeat $r_1, r_2, \ldots$ times respectively is $\frac{n!}{r_1!\, r_2!\, \cdots}$; the total factorial is divided by the factorial of each repeated letter's frequency.
- The Common Operational Trap: Students identify only one repeated letter and omit others (e.g., in MATHEMATICS with two M's, two A's, and two T's, students divide only by $2!$ once instead of $2!\cdot 2!\cdot 2!$), or they apply the raw permutation $n!$ without any correction for repeats.
- **The Golden Rule: Audit every distinct letter individually to record its frequency, then compute $\frac{n!}{(r_1!)(r_2!)\cdots}$, dividing $n!$ by the factorial of every letter that appears more than once.**

## Topic: Basic Probability (Theoretical and Experimental)
- Core Mechanism: Theoretical probability is the ratio of the number of favorable outcomes to the number of total possible outcomes, $P(E) = \frac{\text{favorable outcomes}}{\text{total outcomes}}$; experimental probability substitutes observed frequency and number of trials into the same ratio.
- The Common Operational Trap: When working from a two-way frequency table, students use a row total, a column total, or a subtotal as the denominator rather than the grand total of all cells in the table, computing a conditional probability when a simple probability was requested.
- **The Golden Rule: Sum the entire table to determine the absolute grand total before constructing any fraction; the denominator of a basic probability is always the count of all possible outcomes, not the count within a single row or column.**

## Topic: Probability of Multiple Events – AND (Independent and Dependent)
- Core Mechanism: For independent events (outcome of one does not affect the other), $P(A \text{ and } B) = P(A) \cdot P(B)$; for dependent events (drawing without replacement), $P(A \text{ and } B) = P(A) \cdot P(B \mid A)$, where both the favorable count and the total are updated after the first selection.
- The Common Operational Trap: Students treat dependent events as independent by leaving both the numerator and denominator unchanged for the second draw, failing to reduce the total pool and the count of the favorable outcome after the first item is removed.
- **The Golden Rule: Ask whether removing the first item changes what remains; if it does (no replacement), reduce both the favorable count and the total count by exactly the amount removed before computing the second probability.**

## Topic: Probability of Multiple Events – OR (Mutually Exclusive and Non-Exclusive)
- Core Mechanism: For mutually exclusive events (cannot occur simultaneously), $P(A \text{ or } B) = P(A) + P(B)$; for non-mutually exclusive events that can overlap, $P(A \text{ or } B) = P(A) + P(B) - P(A \text{ and } B)$ to avoid double-counting outcomes where both events hold.
- The Common Operational Trap: Students skip the subtraction step for non-exclusive events, effectively counting the intersection — the outcomes satisfying both $A$ and $B$ — twice in the final probability.
- **The Golden Rule: Always ask first whether $A$ and $B$ can occur simultaneously; if yes, the events are non-exclusive and you must subtract $P(A \text{ and } B)$: $P(A \text{ or } B) = P(A) + P(B) - P(A \text{ and } B)$.**

## Topic: Conditional Probability
- Core Mechanism: $P(A \mid B)$, the probability of $A$ given that $B$ has already occurred, narrows the sample space to only the $B$-outcomes; the denominator becomes the total count of $B$ and the numerator is the count of outcomes where both $A$ and $B$ hold.
- The Common Operational Trap: Students use the grand total of all outcomes as the denominator instead of restricting to only the "given" condition's row or column total, computing a basic probability rather than a conditional one.
- **The Golden Rule: The given condition locks the denominator to that specific row or column total; look only inside that restricted region, count the outcomes satisfying $A$, and divide by the total of the given condition's group — not the entire table's grand total.**

## Topic: Binomial Probability
- Core Mechanism: For a fixed number of independent trials $n$, each with probability of success $p$ (and failure $q = 1 - p$), the probability of exactly $r$ successes is $P(r) = {_{n}}C_{r} \cdot p^{r} \cdot q^{n-r}$; identify all four values of $n$, $r$, $p$, and $q$ explicitly before substituting.
- The Common Operational Trap: For cumulative phrases like "at least $r$" or "at most $r$," students calculate only the single exact value of $P(r)$ rather than summing the formula over every qualifying integer value of $r$, omitting large portions of the total probability.
- **The Golden Rule: List every integer value of $r$ that satisfies the condition ("at most 2" means $r = 0, 1, 2$; "at least 4 of 6" means $r = 4, 5, 6$), evaluate the binomial formula for each, and sum all the results.**

---

## UNIT: RATIONAL EQUATIONS (UNIT 8)

## Topic: Identifying Values Where a Rational Expression is Undefined
- Core Mechanism: A rational expression is undefined at every value of $x$ that makes the denominator equal to zero; factor the denominator completely, set each factor equal to zero, and solve for the excluded values.
- The Common Operational Trap: Students set the numerator equal to zero instead of the denominator, finding $x$-intercept candidates rather than undefined values; they also report the raw quadratic equal to zero without factoring, missing multiple excluded values when the denominator factors into two distinct binomials.
- **The Golden Rule: Factor the denominator completely, set each individual factor $= 0$, and solve — the denominator's zeros are the only values that make the expression undefined, and the numerator plays no role in this step.**

## Topic: Simplifying Rational Expressions
- Core Mechanism: Factor the numerator and denominator completely, then cancel any binomial (or monomial) factor that appears identically in both; the simplified expression is equivalent to the original everywhere the original denominator is nonzero.
- The Common Operational Trap: Students illegally cancel individual terms separated by addition or subtraction (e.g., canceling the $x$ in $\frac{x+5}{x+3}$) rather than factoring first so that numerator and denominator exist as products before any cancellation is attempted.
- **The Golden Rule: You may only cancel a factor that divides every term multiplicatively in both the numerator and the denominator — factor both completely, then cancel matching pairs; never cancel across a plus or minus sign.**

## Topic: Multiplying Rational Expressions
- Core Mechanism: Factor every numerator and denominator individually, combine all factors under a single fraction bar (one large numerator over one large denominator), cancel all matching factor pairs, and then multiply the remaining terms.
- The Common Operational Trap: Students multiply out the expressions before factoring, eliminating the common factors that would cancel and forcing unnecessary polynomial arithmetic; they also miss GCF factors (e.g., the leading $2$ in $2x^2 - 8$) before attempting to cancel.
- **The Golden Rule: Factor all four expressions first, smush them under one fraction bar, cancel every matching pair across the combined numerator and denominator, and only then multiply any surviving factors.**

## Topic: Dividing Rational Expressions
- Core Mechanism: Rewrite the division as multiplication by the reciprocal of the second fraction ("flip and multiply"), then factor, cancel, and simplify exactly as in multiplication.
- The Common Operational Trap: Students skip flipping the second fraction before factoring and attempt to cancel across a division bar, or they accidentally flip the first fraction rather than the second.
- **The Golden Rule: Before touching any algebra, rewrite the entire expression as multiplication by writing "FLIP" and inverting the second fraction only — then proceed with the standard factor-and-cancel routine as if it were a multiplication problem.**

## Topic: Adding and Subtracting Rational Expressions
- Core Mechanism: Factor all denominators to identify the Least Common Denominator (LCD), multiply each fraction's numerator by its missing LCD factor, combine the adjusted numerators over the single LCD, then simplify the resulting expression.
- The Common Operational Trap: During subtraction, students distribute the negative sign to only the first term of the second numerator instead of distributing it across the entire second expression, producing a sign error in every subsequent term of that numerator.
- **The Golden Rule: Enclose the entire second numerator in parentheses before distributing any negative — $\frac{a}{d} - \frac{b+c}{d} = \frac{a - (b + c)}{d} = \frac{a - b - c}{d}$ — so every term of the second fraction is correctly negated.**

## Topic: Identifying Features of Rational Functions (Holes, VA, HA, and Intercepts)
- Core Mechanism: Factor numerator and denominator; common factors that cancel create holes (use the reduced function to find the $y$-coordinate); remaining denominator-only factors create vertical asymptotes; comparing numerator and denominator degree determines the horizontal asymptote; numerator zeros give $x$-intercepts and evaluating at $x = 0$ gives the $y$-intercept.
- The Common Operational Trap: Students confuse holes with vertical asymptotes — mistakenly calling a cancelled factor a VA and an uncancelled factor a hole — and when computing the $y$-coordinate of a hole they substitute the hole's $x$-value into the original (unreduced) function, obtaining $\frac{0}{0}$ instead of using the reduced form.
- **The Golden Rule: Cancelled factor $\Rightarrow$ hole (substitute its $x$-value into the reduced function for the $y$-coordinate); uncancelled denominator factor $\Rightarrow$ VA; the hole always wins over an $x$-intercept at the same location, and the VA always wins over a hole.**

## Topic: Horizontal Asymptote Rules (Degree Comparison)
- Core Mechanism: The horizontal asymptote of $f(x) = \frac{ax^n + \cdots}{bx^d + \cdots}$ depends on comparing the degree of the numerator $n$ to the degree of the denominator $d$: if $d > n$ (bottom-heavy), $y = 0$; if $n = d$ (equal), $y = \frac{a}{b}$ (ratio of leading coefficients); if $n > d$ (top-heavy), there is no HA.
- The Common Operational Trap: Students apply the leading-coefficient ratio $y = \frac{a}{b}$ in all three cases without first comparing degrees, or they incorrectly use the degree comparison result as the asymptote value rather than the leading-coefficient ratio when degrees are equal.
- **The Golden Rule: Check the degrees first — only when $n = d$ do you use $y = \frac{\text{leading coeff of numerator}}{\text{leading coeff of denominator}}$; bottom-heavy always yields $y = 0$; top-heavy always yields no HA, full stop.**

## Topic: Graphing Rational Functions
- Core Mechanism: Plot all five identified features (hole as an open circle, vertical asymptote as a dashed vertical line, horizontal asymptote as a dashed horizontal line, $x$-intercepts, and $y$-intercept), then test one $x$-value in each region bounded by the VAs to determine whether each branch lies above or below the HA.
- The Common Operational Trap: Students sketch branches without testing a point in each region, drawing branches on the wrong side of the horizontal asymptote; they also fail to approach the vertical asymptote from both sides separately and instead draw a single continuous curve that crosses through it.
- **The Golden Rule: In every interval separated by a vertical asymptote, substitute one test $x$-value into the reduced function — the sign of the output determines whether the branch lies above or below the HA in that region; branches approach but never cross any asymptote.**

---

## UNIT: EXPONENTIAL AND LOGARITHMIC EQUATIONS (UNIT 7)

## Topic: Evaluating Logarithmic Expressions
- Core Mechanism: Evaluate $\log_b(y)$ by asking "to what power must $b$ be raised to produce $y$?"; special cases include $\log_b(1) = 0$, $\log_b(b) = 1$, $\log_b(b^x) = x$, $\ln(e^x) = x$, and $\log_b(0)$ is undefined.
- The Common Operational Trap: Students evaluate $\log_b(y)$ by dividing $y$ by $b$ arithmetically rather than identifying an exponent; they also confuse $\log$ (implied base 10) with $\ln$ (base $e$), leading to incorrect base substitutions.
- **The Golden Rule: Convert $\log_b(y) = x$ to its exponential equivalent $b^x = y$ and solve for $x$; when no base is written, $\log$ defaults to base 10 and $\ln$ defaults to base $e$.**

## Topic: Expanding Logarithmic Expressions
- Core Mechanism: Apply the three log properties in the "breakapart" direction to expand a complex expression into a sum or difference of simpler ones: $\log_b(MN) = \log_b M + \log_b N$, $\log_b\!\left(\frac{M}{N}\right) = \log_b M - \log_b N$, and $\log_b(M^c) = c\log_b M$.
- The Common Operational Trap: Students attempt to expand $\log_b(M + N)$ or $\log_b(M - N)$ using the product or quotient rule, incorrectly treating addition inside the argument as if it were multiplication; the product and quotient rules apply only when the argument is a product or quotient, never a sum or difference.
- **The Golden Rule: You may only split a log argument using the product or quotient rule if the terms inside are connected by multiplication or division — $\log(xy)$ expands, but $\log(x + y)$ cannot be split at all.**

## Topic: Condensing Logarithmic Expressions
- Core Mechanism: Apply log properties in reverse to collapse a sum or difference of logs into a single logarithm: first use the power rule to move coefficients to exponents, then combine using the product rule for addition and the quotient rule for subtraction.
- The Common Operational Trap: Students add the arguments of the logs rather than multiplying them when condensing a sum (e.g., writing $\log 3 + \log 5 = \log 8$ instead of $\log 15$), or they move the coefficient inside the argument as an additive constant rather than as an exponent.
- **The Golden Rule: Coefficients become exponents first via the power rule; then $\log_b M + \log_b N = \log_b(M \cdot N)$ (multiply arguments) and $\log_b M - \log_b N = \log_b\!\left(\frac{M}{N}\right)$ (divide arguments).**

## Topic: Solving Exponential Equations
- Core Mechanism: Isolate the entire exponential expression on one side of the equation (dividing out any coefficient that multiplies it), then take $\log_b$ of both sides to bring the variable exponent down as a coefficient, and solve algebraically.
- The Common Operational Trap: Students apply the logarithm before fully isolating the base-and-exponent term — taking the log while a coefficient such as $2$ or $3$ still multiplies the exponential — which distributes the log incorrectly over addition rather than over the argument.
- **The Golden Rule: Isolate the exponential term completely (divide out any multiplying number first), then apply $\log_b$ to both sides and use $\log_b(b^x) = x$ to resolve the left side directly.**

## Topic: Solving Logarithmic Equations
- Core Mechanism: Use log properties to condense the equation into a single logarithm on one side, convert to exponential form ($\log_b y = x \Leftrightarrow b^x = y$), solve the resulting algebraic equation, then verify all solutions in the original equation.
- The Common Operational Trap: Students accept solutions that create a zero or negative argument inside a logarithm in the original equation, not accounting for the strict domain restriction that all logarithmic arguments must be strictly positive (domain is $(0, \infty)$).
- **The Golden Rule: After solving algebraically, substitute every candidate $x$-value back into every original logarithm and confirm that every argument is strictly positive — any solution producing a zero or negative argument is extraneous and must be rejected.**

## Topic: Exponential Growth and Decay Applications
- Core Mechanism: Model real-world scenarios without a stated compounding frequency using $A = P(1 + r)^t$ for growth or $A = P(1 - r)^t$ for decay, where $P$ is the initial value, $r$ is the decimal rate, and $t$ is time; solve for the unknown variable using logarithms.
- The Common Operational Trap: Students substitute the rate as a whole-number percent (e.g., $r = 4.2$ instead of $r = 0.042$) or confuse the growth model with the compound interest formula by inserting an unnecessary $n$ compounding period when none is stated.
- **The Golden Rule: Convert every percentage rate to a decimal before substituting, confirm the sign ($+$ for growth, $-$ for decay), and use the basic $A = P(1 \pm r)^t$ model only when no compounding frequency is specified.**

## Topic: Compound Interest (Periodic and Continuous)
- Core Mechanism: Periodic compounding uses $A = P\!\left(1 + \frac{r}{n}\right)^{nt}$ where $n$ is the number of compounding periods per year; continuous compounding uses $A = Pe^{rt}$ where $e$ is Euler's number; solve for the unknown using logarithms when needed.
- The Common Operational Trap: Students apply the periodic formula to a problem that specifies "compounded continuously," or they select an incorrect value of $n$ (e.g., using $n = 1$ for a monthly-compounded account that requires $n = 12$).
- **The Golden Rule: If the problem states "compounded continuously," use $A = Pe^{rt}$ exclusively; otherwise identify $n$ explicitly from the compounding period (annually: $n=1$; quarterly: $n=4$; monthly: $n=12$; daily: $n=365$) before substituting into $A = P(1+\frac{r}{n})^{nt}$.**

---

## UNIT: RADICAL FUNCTIONS (UNIT 6B)

## Topic: Solving Radical (Square Root) Equations
- Core Mechanism: Isolate the radical expression completely on one side of the equation, raise both sides to the power matching the index to eliminate the radical, solve the resulting polynomial equation, and verify every solution in the original un-raised equation to check for extraneous roots.
- The Common Operational Trap: Students square both sides before isolating the radical, making the algebra significantly more complex; and when a variable exists outside the radical (e.g., $x + \sqrt{x+3} = 3$), they neglect to check solutions, missing extraneous values introduced by the squaring process.
- **The Golden Rule: Isolate the radical on one side first — always — then raise both sides to the appropriate power; after solving, substitute every candidate solution into the original equation and discard any that produce a false statement.**

## Topic: Domain of Radical Functions
- Core Mechanism: For even-index radicals, the radicand must be $\geq 0$; set the radicand $\geq 0$, solve the inequality for $x$, and express the result in interval notation; if the radical is in the denominator, the radicand must be strictly $> 0$ to also avoid division by zero.
- The Common Operational Trap: Students use $\geq 0$ for a radical in the denominator (allowing the denominator to equal zero and making the function undefined) or fail to flip the inequality sign when dividing both sides by a negative coefficient while isolating $x$.
- **The Golden Rule: Numerator radical: set radicand $\geq 0$; denominator radical: set radicand $> 0$ (strict inequality); solve the inequality and flip the sign if you divide by a negative — express the answer in interval notation.**

## Topic: Domain of Rational Functions
- Core Mechanism: A rational function $f(x) = \frac{P(x)}{Q(x)}$ is undefined wherever $Q(x) = 0$; factor the denominator completely, set each factor $\neq 0$, solve for the excluded values, and write the domain in interval notation using union symbols to join the permitted intervals.
- The Common Operational Trap: Students factor the numerator and exclude those values, or they factor a linear denominator but fail to factor a quadratic denominator, missing one or both of the restricted values.
- **The Golden Rule: Factor the denominator completely and find every value of $x$ that makes any denominator factor equal zero; those are the only excluded values — the domain is all reals except those points, written with interval notation and $\cup$ symbols.**

## Topic: Operations with Functions (Add, Subtract, Multiply, Divide)
- Core Mechanism: Two functions are combined algebraically: $(f+g)(x) = f(x) + g(x)$, $(f-g)(x) = f(x) - g(x)$, $(f \cdot g)(x) = f(x) \cdot g(x)$, and $\left(\frac{f}{g}\right)(x) = \frac{f(x)}{g(x)}$ where $g(x) \neq 0$; then simplify by combining like terms.
- The Common Operational Trap: When computing $(f - g)(x)$, students negate only the first term of $g(x)$ — treating it as though only the leading term is subtracted — rather than distributing the negative through every term of the entire function $g(x)$.
- **The Golden Rule: Place the entire second function inside parentheses before subtracting: $(f - g)(x) = f(x) - [g(x)]$, then distribute the negative through every single term of $g(x)$.**

## Topic: Composition of Functions
- Core Mechanism: $(f \circ g)(x) = f(g(x))$ is evaluated by substituting the entire expression $g(x)$ into every $x$-position in $f$; evaluate from the inside out — compute the inner function's value or expression first, then feed the result into the outer function.
- The Common Operational Trap: Students evaluate in the wrong order (outer function first), or when substituting a binomial $g(x)$ into $f(x) = x^2$, they square only the first term of the binomial instead of squaring the entire binomial using FOIL.
- **The Golden Rule: Work strictly inside-out; substitute $g(x)$ into every $x$ in $f$, wrapping the substitution in parentheses, so that squaring or distributing applies to the whole expression: $f(g(x)) \neq g(f(x))$ — order is critical.**

## Topic: Inverse Functions
- Core Mechanism: Find $f^{-1}(x)$ by replacing $f(x)$ with $y$, interchanging $x$ and $y$, solving algebraically for $y$, and renaming the result $f^{-1}(x)$; the composition property confirms the result: $f(f^{-1}(x)) = x$.
- The Common Operational Trap: When $y$ appears in multiple terms of a rational function after swapping (e.g., $x(y+3) = y$ expands to $xy + 3x = y$), students fail to collect all $y$-terms on one side and factor $y$ out before dividing, leaving the solution algebraically incomplete.
- **The Golden Rule: After swapping $x$ and $y$, move every term containing $y$ to one side, factor $y$ out of all those terms as a product, then divide both sides by the remaining factor — this factoring step is mandatory any time $y$ appears in two separate terms.**

## Topic: Graphing Radical Functions (Square Root and Cube Root)
- Core Mechanism: For $f(x) = a\sqrt{x - h} + k$ and $f(x) = a\sqrt[3]{x - h} + k$, the anchor point shifts right $h$ units and up $k$ units from the parent function's origin; a negative value of $a$ reflects the graph over the $x$-axis; the square root's domain begins at the anchor point, while the cube root extends over all reals.
- The Common Operational Trap: Students reverse the direction of the horizontal shift — interpreting $\sqrt{x + 3}$ as a right shift of 3 when it actually shifts left 3 — because they apply the sign inside the radical directly rather than recognizing it as $x - (-3)$.
- **The Golden Rule: Rewrite the argument in the form $(x - h)$: the shift is always the opposite sign of what appears inside — $(x - 3)$ moves right 3, $(x + 3) = (x - (-3))$ moves left 3; vertical shifts $+k$ and $-k$ follow their sign directly.**

---

## UNIT: ROOTS AND RADICALS (UNIT 6A)

## Topic: Simplifying Radicals – Integer Radicands
- Core Mechanism: Build a complete prime factorization of the radicand, group the prime factors into complete sets of $n$ (where $n$ is the index), bring each complete group out from under the radical as a single factor, and leave any remaining primes inside.
- The Common Operational Trap: Students stop after extracting the first recognized perfect-power factor without verifying that all complete groups have been pulled out (e.g., simplifying $\sqrt{72}$ as $3\sqrt{8}$ instead of the fully simplified $6\sqrt{2}$); they also confuse the grouping size when the index is 3 or 4 rather than 2.
- **The Golden Rule: Complete the entire prime factorization tree; for index $n$, every group of $n$ identical primes exits the radical as one factor — repeat until no $n$-group remains inside.**

## Topic: Simplifying Radicals – Variable Radicands
- Core Mechanism: Divide the variable's exponent by the index; the quotient becomes the exponent on the factor pulled outside the radical and the remainder becomes the exponent left inside: $\sqrt[n]{x^p} = x^{q}\sqrt[n]{x^{r}}$ where $p = nq + r$.
- The Common Operational Trap: Students leave a variable under the radical whose exponent equals or exceeds the index (e.g., leaving $\sqrt{x^6}$ unresolved instead of writing $x^3$); for odd exponents, they fail to split the variable into the largest even power times $x^1$ before extracting.
- **The Golden Rule: Divide the exponent by the index — the quotient exits as a power in front, and the remainder (if any) stays inside the radical: $\sqrt{x^7} = x^3\sqrt{x}$ because $7 \div 2$ gives quotient $3$, remainder $1$.**

## Topic: Multiplying Radicals (Single-Term)
- Core Mechanism: Radicals with identical indexes multiply by combining under a single radical symbol: $\sqrt[n]{a} \cdot \sqrt[n]{b} = \sqrt[n]{ab}$; multiply integer coefficients together and radicands together separately, then simplify the resulting radical if possible.
- The Common Operational Trap: Students attempt to multiply radicals with different indexes (e.g., $\sqrt{5} \cdot \sqrt[3]{5}$, which cannot be directly combined), or they multiply a coefficient by a radicand instead of keeping coefficient $\times$ coefficient and radicand $\times$ radicand as separate operations.
- **The Golden Rule: Confirm that indexes match before multiplying; then multiply coefficient by coefficient and radicand by radicand as completely separate operations, and simplify the resulting product radical.**

## Topic: Dividing Radicals and Rationalizing Single-Term Denominators
- Core Mechanism: Simplify by rewriting as a single radical over its denominator ($\frac{\sqrt[n]{a}}{\sqrt[n]{b}} = \sqrt[n]{\frac{a}{b}}$), then eliminate any radical from the denominator by multiplying numerator and denominator by the exact radical needed to produce a perfect $n$th power in the denominator.
- The Common Operational Trap: For a cube root in the denominator, students multiply by $\frac{\sqrt[3]{b}}{\sqrt[3]{b}}$, producing $\sqrt[3]{b^2}$ in the denominator (still irrational) instead of multiplying by $\frac{\sqrt[3]{b^2}}{\sqrt[3]{b^2}}$ to produce $\sqrt[3]{b^3} = b$.
- **The Golden Rule: To clear $\sqrt[n]{b^k}$ from the denominator, multiply by $\frac{\sqrt[n]{b^{n-k}}}{\sqrt[n]{b^{n-k}}}$ so the denominator becomes $\sqrt[n]{b^n} = b$; for square roots ($n = 2$, $k = 1$), simply multiply by $\frac{\sqrt{b}}{\sqrt{b}}$.**

## Topic: Adding and Subtracting Radicals
- Core Mechanism: Simplify every radical term to its minimum form first, then identify like radical terms — those sharing both an identical index and an identical radicand — and combine them by adding or subtracting their integer coefficients while leaving the radical factor unchanged.
- The Common Operational Trap: Students add radicands directly as if the radical were a variable (e.g., writing $\sqrt{50} + \sqrt{18} = \sqrt{68}$ instead of $5\sqrt{2} + 3\sqrt{2} = 8\sqrt{2}$), or they declare terms unlike before simplifying each completely, missing the hidden matching radicand.
- **The Golden Rule: Fully simplify every radical term before comparing; only after all terms are in their simplest form should you check for matching index-and-radicand pairs, and then add or subtract only the front coefficients — the radicand never changes.**

## Topic: Multiplying Binomial Radical Expressions (FOIL)
- Core Mechanism: Expand products like $(a + \sqrt{b})(c - \sqrt{d})$ using the FOIL method, multiplying each pair of terms systematically; when two identical radicals multiply ($\sqrt{b} \cdot \sqrt{b}$), the result is the integer $b$, eliminating the radical.
- The Common Operational Trap: Students square a binomial like $(3 + \sqrt{5})^2$ as $9 + 5 = 14$ without generating the middle cross term $2(3)(\sqrt{5}) = 6\sqrt{5}$, because they apply the shortcut $a^2 + b^2$ instead of the correct $(a + b)^2 = a^2 + 2ab + b^2$.
- **The Golden Rule: Execute all four FOIL products individually and explicitly; $\sqrt{b} \cdot \sqrt{b} = b$ (produces an integer, not $\sqrt{b^2}$ left under a radical), and squaring a binomial always generates a middle term — never skip it.**

## Topic: Dividing Binomial Radical Expressions (Rationalizing with Conjugates)
- Core Mechanism: To rationalize a binomial denominator containing a radical, multiply both the numerator and denominator by the conjugate of the denominator (same two terms, middle sign flipped), exploiting the difference-of-squares identity $(a + \sqrt{b})(a - \sqrt{b}) = a^2 - b$ to eliminate the radical from the denominator.
- The Common Operational Trap: Students multiply by only the radical part of the denominator (e.g., multiplying by $\frac{\sqrt{b}}{\sqrt{b}}$ when the denominator is $a + \sqrt{b}$) instead of by the full conjugate, leaving an irrational cross term in the denominator.
- **The Golden Rule: The conjugate is the complete denominator binomial with its middle sign reversed — multiply both top and bottom by the entire conjugate; the product of conjugates always produces $a^2 - b$ with no radicals remaining in the denominator.**

## Topic: Rational Exponents
- Core Mechanism: A rational exponent $\frac{m}{n}$ encodes both a power and a root simultaneously: $x^{m/n} = \sqrt[n]{x^m} = \!\left(\sqrt[n]{x}\right)^m$; the denominator of the fraction is the index of the radical (the root) and the numerator is the power applied to the base.
- The Common Operational Trap: Students swap the positions of the power and root, writing the numerator as the index and the denominator as the exponent and producing $x^{n/m}$ instead of $x^{m/n}$; they also fail to recognize that a negative rational exponent inverts the expression: $x^{-m/n} = \frac{1}{x^{m/n}}$.
- **The Golden Rule: Read $x^{m/n}$ as $\frac{\text{power}}{\text{root}}$ — the denominator of the fractional exponent is always the index (root) of the radical; if the exponent is negative, place the base in the denominator with a positive exponent.**
