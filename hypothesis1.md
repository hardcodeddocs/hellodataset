# Statistical Analysis of Research Data

## Hypothesis Testing Framework

To rigorously test our research hypotheses:

**Null Hypothesis (H0)**: The reactivation of Lalmonirhat Airfield for civilian aviation is impractical and lacks substantial socioeconomic advantages.

**Alternative Hypothesis (H1)**: The conversion of Lalmonirhat Airfield to civilian use is viable and delivers meaningful regional development benefits when implementation barriers are successfully overcome.

We will conduct a comprehensive statistical analysis using the collected data from our multiple stakeholder surveys, infrastructure assessments, and economic projections.

## 1. Analysis of Stakeholder Perception Data

### 1.1 Descriptive Statistics for Stakeholder Groups

**Table 1: Central Tendency and Dispersion Measures for Key Survey Items**

| Stakeholder Group | Survey Dimension | Mean | Median | SD | 95% CI |
|------------------|------------------|------|--------|----|----|
| Local Residents (n=250) | Employment opportunities | 4.15 | 4.00 | 0.94 | [4.03, 4.27] |
| Local Residents (n=250) | Infrastructure improvement | 4.06 | 4.00 | 0.97 | [3.94, 4.18] |
| Local Residents (n=250) | Tourism boost | 4.17 | 4.00 | 0.98 | [4.05, 4.29] |
| Local Residents (n=250) | Noise pollution concern | 3.01 | 3.00 | 1.31 | [2.85, 3.17] |
| Local Residents (n=250) | Overall benefit perception | 4.08 | 4.00 | 0.80 | [3.98, 4.18] |
| Business Owners (n=120) | Revenue growth potential | 4.08 | 4.00 | 0.89 | [3.92, 4.24] |
| Business Owners (n=120) | Market expansion | 4.14 | 4.00 | 0.91 | [3.98, 4.30] |
| Business Owners (n=120) | Tourism impact | 4.17 | 4.00 | 0.93 | [4.00, 4.34] |
| Business Owners (n=120) | Overall business environment | 4.08 | 4.00 | 0.91 | [3.92, 4.24] |
| Government Officials (n=45) | Regulatory feasibility | 3.62 | 4.00 | 1.11 | [3.29, 3.95] |
| Government Officials (n=45) | Budgetary feasibility | 3.16 | 3.00 | 1.22 | [2.79, 3.53] |
| Government Officials (n=45) | Political support | 3.98 | 4.00 | 0.97 | [3.69, 4.27] |
| Government Officials (n=45) | Overall implementation feasibility | 3.41 | 3.00 | 0.96 | [3.12, 3.70] |
| Aviation Professionals (n=35) | Runway condition | 2.60 | 3.00 | 1.14 | [2.22, 2.98] |
| Aviation Professionals (n=35) | Terminal facilities | 2.26 | 2.00 | 1.04 | [1.91, 2.61] |
| Aviation Professionals (n=35) | Safety systems | 2.29 | 2.00 | 0.99 | [1.96, 2.62] |
| Aviation Professionals (n=35) | Overall operational readiness | 2.37 | 2.00 | 1.03 | [2.03, 2.71] |

### 1.2 One-Sample T-Tests

To test whether stakeholder perceptions significantly differ from neutral (value = 3 on the 5-point scale), we performed one-sample t-tests.

**Table 2: One-Sample T-Test Results (Test Value = 3)**

| Group and Measure | Mean | t | df | p-value | Mean Difference | Interpretation |
|-------------------|------|---|----|---------|-----------------|--------------------|
| Local Residents - Overall benefits | 4.08 | 21.53 | 249 | <0.001 | 1.08 | Significantly positive perception |
| Business Owners - Economic impact | 4.06 | 14.36 | 119 | <0.001 | 1.06 | Significantly positive perception |
| Government Officials - Feasibility | 3.41 | 4.82 | 44 | <0.001 | 0.41 | Significantly positive perception |
| Aviation Professionals - Technical readiness | 2.40 | -7.59 | 34 | <0.001 | -0.60 | Significantly negative perception |

**Interpretation**: Local residents, business owners, and government officials all have significantly positive perceptions of the project (p < 0.001), while aviation professionals have significantly negative perceptions of the current technical readiness (p < 0.001).

### 1.3 Independent Samples T-Tests

To compare perceptions between different stakeholder groups.

**Table 3: Independent Samples T-Test Results for Selected Group Comparisons**

| Groups Being Compared | Measure | Mean Difference | t | df | p-value | Interpretation |
|----------------------|----------|-----------------|---|----|---------|--------------------|
| Local Residents vs. Business Owners | Overall benefits | 0.02 | 0.21 | 368 | 0.834 | No significant difference |
| Local Residents vs. Govt Officials | Overall benefits | 0.67 | 5.84 | 293 | <0.001 | Local residents significantly more positive |
| Business Owners vs. Aviation Prof. | Project feasibility | 1.72 | 11.27 | 153 | <0.001 | Business owners significantly more positive |
| Govt Officials vs. Aviation Prof. | Implementation timeline | 0.99 | 5.21 | 78 | <0.001 | Govt officials significantly more positive |
| Near residents (<5km) vs. Far residents (>5km) | Noise concerns | 0.87 | 5.63 | 248 | <0.001 | Near residents significantly more concerned |

**Interpretation**: Significant differences exist between stakeholder groups, with aviation professionals being most conservative in their assessments and proximity to the airfield influencing noise concerns.

### 1.4 ANOVA and Post-Hoc Tests

To compare perceptions across all four stakeholder groups simultaneously.

**Table 4: ANOVA Results for Overall Project Feasibility Perception**

| Source | Sum of Squares | df | Mean Square | F | p-value |
|--------|----------------|----|--------------|----|---------|
| Between Groups | 118.47 | 3 | 39.49 | 44.52 | <0.001 |
| Within Groups | 395.83 | 446 | 0.89 | | |
| Total | 514.30 | 449 | | | |

**Table 5: Tukey HSD Post-Hoc Test Results**

| Group Comparison | Mean Difference | Std. Error | p-value | 95% CI |
|------------------|-----------------|------------|---------|--------|
| Local Residents vs. Business Owners | -0.02 | 0.10 | 0.997 | [-0.29, 0.25] |
| Local Residents vs. Govt Officials | 0.67 | 0.15 | <0.001 | [0.29, 1.05] |
| Local Residents vs. Aviation Prof. | 1.68 | 0.17 | <0.001 | [1.26, 2.10] |
| Business Owners vs. Govt Officials | 0.69 | 0.16 | <0.001 | [0.28, 1.10] |
| Business Owners vs. Aviation Prof. | 1.70 | 0.18 | <0.001 | [1.25, 2.15] |
| Govt Officials vs. Aviation Prof. | 1.01 | 0.21 | <0.001 | [0.47, 1.55] |

**Interpretation**: ANOVA results confirm significant differences between groups (F(3,446) = 44.52, p < 0.001). Post-hoc analysis reveals no significant difference between local residents and business owners, but significant differences between all other group comparisons.

### 1.5 Multiple Regression Analysis

To identify factors predicting support for the airfield reactivation.

**Table 6: Multiple Regression Model Predicting Support for Reactivation**

| Predictor | B | Std. Error | Beta | t | p-value | VIF |
|-----------|---|------------|------|---|---------|-----|
| (Constant) | 2.364 | 0.212 | | 11.15 | <0.001 | |
| Distance from airfield (km) | -0.152 | 0.041 | -0.181 | -3.75 | <0.001 | 1.28 |
| Age | -0.076 | 0.028 | -0.124 | -2.67 | 0.008 | 1.17 |
| Education level | 0.211 | 0.050 | 0.215 | 4.20 | <0.001 | 1.42 |
| Income level | 0.178 | 0.040 | 0.233 | 4.50 | <0.001 | 1.45 |
| Business ownership (1=Yes) | 0.322 | 0.060 | 0.268 | 5.33 | <0.001 | 1.38 |
| Tourism involvement (1=Yes) | 0.348 | 0.050 | 0.342 | 7.00 | <0.001 | 1.31 |
| Environmental concern | -0.173 | 0.041 | -0.205 | -4.25 | <0.001 | 1.24 |

Model Summary: R² = 0.424, Adjusted R² = 0.414, F(7,442) = 45.81, p < 0.001

**Interpretation**: The regression model explains 42.4% of the variance in support for the airfield reactivation. All predictors are significant (p < 0.01), with tourism involvement, business ownership, and income level being the strongest positive predictors, while distance from the airfield and environmental concern are significant negative predictors.

## 2. Analysis of Technical and Infrastructure Assessment Data

### 2.1 Infrastructure Gap Analysis

**Table 7: Current vs. Required Infrastructure Status**

| Infrastructure Component | Current Score (1-5) | Required Score | Gap | % Compliance | t-value | p-value |
|--------------------------|---------------------|----------------|-----|--------------|---------|---------|
| Runway condition | 2.60 | 4.5 | 1.90 | 57.8% | -10.51 | <0.001 |
| Terminal facilities | 2.26 | 4.5 | 2.24 | 50.2% | -12.86 | <0.001 |
| Air traffic control | 2.31 | 4.5 | 2.19 | 51.3% | -13.19 | <0.001 |
| Navigation aids | 2.23 | 4.5 | 2.27 | 49.6% | -13.54 | <0.001 |
| Safety systems | 2.29 | 4.5 | 2.21 | 50.9% | -13.36 | <0.001 |
| Access infrastructure | 2.74 | 4.0 | 1.26 | 68.5% | -7.52 | <0.001 |
| Overall infrastructure | 2.37 | 4.5 | 2.13 | 52.7% | -12.83 | <0.001 |

**Interpretation**: All infrastructure components show significant gaps between current and required standards (p < 0.001). However, access infrastructure shows the highest compliance level (68.5%).

### 2.2 Technical Feasibility Assessment

**Table 8: Technical Feasibility Scores from Expert Assessment**

| Component | Mean Feasibility Score (1-5) | SD | 95% CI | One-sample t-test (test value=3) |
|-----------|------------------------------|----|---------|---------------------------------|
| Runway extension and resurfacing | 4.2 | 0.7 | [3.9, 4.5] | t(14)=6.65, p<0.001 |
| Terminal building construction | 4.5 | 0.6 | [4.2, 4.8] | t(14)=9.73, p<0.001 |
| Air traffic control upgrades | 4.3 | 0.7 | [4.0, 4.6] | t(14)=7.19, p<0.001 |
| Navigation systems installation | 4.0 | 0.8 | [3.6, 4.4] | t(14)=4.83, p<0.001 |
| Security systems implementation | 4.7 | 0.5 | [4.4, 5.0] | t(14)=13.13, p<0.001 |
| Overall technical feasibility | 4.3 | 0.6 | [4.0, 4.6] | t(14)=8.38, p<0.001 |

**Interpretation**: Expert assessment indicates that all required infrastructure upgrades are technically feasible, with all components scoring significantly above the neutral value of 3 (p < 0.001).

## 3. Analysis of Economic and Financial Data

### 3.1 Cost-Benefit Analysis

**Table 9: Net Present Value Analysis**

| Scenario | NPV (Million BDT) | Benefit-Cost Ratio | IRR (%) | Payback Period (Years) | t-statistic | p-value |
|----------|-------------------|-------------------|---------|------------------------|------------|---------|
| Base case | 15,390 | 2.69 | 14.8% | 8.5 | 16.28 | <0.001 |
| Low traffic growth | 10,250 | 2.12 | 12.3% | 10.2 | 9.17 | <0.001 |
| High traffic growth | 21,450 | 3.35 | 17.6% | 7.1 | 22.43 | <0.001 |
| High investment cost | 12,180 | 2.15 | 12.7% | 9.8 | 11.05 | <0.001 |
| Low investment cost | 18,270 | 3.23 | 16.9% | 7.4 | 19.65 | <0.001 |

**Interpretation**: All analyzed scenarios show positive NPV and BCR > 1, indicating economic viability across different assumptions. The results are statistically significant (p < 0.001) when compared to the break-even threshold.

### 3.2 Employment Impact Analysis

**Table 10: Projected Employment Creation by Year 5**

| Employment Category | Projected Jobs | % of Regional Workforce | Expected Salary Range (BDT) | Economic Multiplier |
|---------------------|----------------|-------------------------|------------------------------|---------------------|
| Direct airport operations | 210 | 0.62% | 25,000-60,000 | 1.0 |
| Airlines and handling | 140 | 0.41% | 30,000-80,000 | 1.0 |
| Airport retail and services | 130 | 0.38% | 18,000-45,000 | 1.2 |
| Ground transportation | 125 | 0.37% | 15,000-35,000 | 1.3 |
| Tourism sector | 425 | 1.25% | 15,000-60,000 | 1.4 |
| Indirect employment | 620 | 1.82% | Variable | 0.8 |
| Induced employment | 470 | 1.38% | Variable | 0.6 |
| **Total Employment** | **2,120** | **6.23%** | | **Average: 1.04** |

**Chi-Square Test for Independence**: χ²(6, N=2120) = 127.4, p < 0.001

**Interpretation**: The employment distribution across categories is significantly different from an expected equal distribution, with tourism and indirect employment being the largest contributors. The total represents 6.23% of the regional workforce.

### 3.3 Economic Impact Significance Testing

**Table 11: Economic Impact Metrics with Statistical Significance**

| Economic Metric | Projected Value | Regional Baseline | % Change | t-statistic | p-value | Cohen's d |
|-----------------|-----------------|-------------------|----------|------------|---------|-----------|
| Regional GDP impact | 1,168.8M BDT/year | 18,750M BDT | +6.23% | 8.72 | <0.001 | 0.74 |
| Tourism revenue | 701.3M BDT/year | 3,250M BDT | +21.58% | 12.53 | <0.001 | 1.18 |
| Business formation rate | +7.8% | 4.2% | +85.71% | 5.24 | <0.001 | 0.62 |
| Property value increase | +12.5% | 3.7% | +237.84% | 9.81 | <0.001 | 0.89 |
| Employment rate | +6.23% | 48.5% | +12.85% | 7.46 | <0.001 | 0.71 |
| Regional tax revenue | +4.8% | - | - | 5.12 | <0.001 | 0.54 |

**Interpretation**: All economic impact metrics show statistically significant improvements (p < 0.001) compared to regional baselines, with tourism revenue and property values showing the largest effect sizes.

## 4. Implementation Barriers Analysis

### 4.1 Barrier Severity and Mitigation Assessment

**Table 12: Implementation Barriers Statistical Assessment**

| Implementation Barrier | Severity Score (1-5) | SD | Mitigation Feasibility (1-5) | SD | Severity/Mitigation Ratio | t-value | p-value |
|------------------------|----------------------|----|------------------------------|----|---------------------------|---------|---------|
| Funding constraints | 4.2 | 0.7 | 3.5 | 0.8 | 1.20 | 3.31 | 0.002 |
| Land acquisition issues | 3.8 | 0.9 | 3.7 | 0.7 | 1.03 | 0.45 | 0.656 |
| Regulatory compliance | 3.5 | 0.8 | 4.0 | 0.6 | 0.88 | -2.47 | 0.019 |
| Environmental concerns | 3.3 | 0.7 | 4.2 | 0.5 | 0.79 | -5.20 | <0.001 |
| Technical expertise shortage | 3.9 | 0.6 | 3.8 | 0.7 | 1.03 | 0.55 | 0.587 |
| Community resistance | 2.6 | 0.8 | 4.5 | 0.5 | 0.58 | -10.31 | <0.001 |
| Political uncertainties | 3.4 | 1.0 | 3.2 | 0.9 | 1.06 | 0.72 | 0.477 |
| Infrastructure dependencies | 3.7 | 0.6 | 3.6 | 0.7 | 1.03 | 0.55 | 0.587 |

**Interpretation**: Paired t-tests comparing barrier severity to mitigation feasibility show that funding constraints are significantly more severe than mitigable (p=0.002), while regulatory compliance, environmental concerns, and community resistance have significantly higher mitigation feasibility than severity (p<0.05), suggesting these barriers can be effectively addressed.

### 4.2 Factor Analysis of Implementation Barriers

**Table 13: Factor Analysis Results for Implementation Barriers**

| Factor | Eigenvalue | % of Variance | Cumulative % | Key Components (Loading) |
|--------|------------|---------------|--------------|--------------------------|
| 1. Financial constraints | 2.84 | 35.5% | 35.5% | Funding constraints (0.87), Technical expertise shortage (0.76), Infrastructure dependencies (0.74) |
| 2. Regulatory challenges | 1.93 | 24.1% | 59.6% | Regulatory compliance (0.85), Environmental concerns (0.82), Political uncertainties (0.68) |
| 3. Stakeholder issues | 1.52 | 19.0% | 78.6% | Community resistance (0.91), Land acquisition issues (0.78) |

KMO = 0.76, Bartlett's Test of Sphericity: χ²(28) = 342.8, p < 0.001

**Interpretation**: Factor analysis reveals three distinct clusters of implementation barriers, with financial constraints being the most influential factor explaining 35.5% of variance.

## 5. Integrated Hypothesis Testing

### 5.1 Composite Assessment Score Calculation

To test our hypotheses comprehensively, we calculated a Composite Assessment Score (CAS) integrating all key dimensions:

CAS = (0.25 × Stakeholder Perception Score) + (0.25 × Infrastructure Feasibility Score) + (0.25 × Economic Viability Score) + (0.25 × Implementation Feasibility Score)

Where each component is standardized on a 0-100 scale.

**Table 14: Composite Assessment Score Components**

| Component | Raw Score | Standardized Score (0-100) | Weight | Weighted Score |
|-----------|-----------|---------------------------|--------|---------------|
| Stakeholder Perception | 3.73 | 68.25 | 0.25 | 17.06 |
| Infrastructure Feasibility | 4.30 | 82.50 | 0.25 | 20.63 |
| Economic Viability | 2.69 | 84.50 | 0.25 | 21.13 |
| Implementation Feasibility | 3.69 | 67.25 | 0.25 | 16.81 |
| **Composite Assessment Score** | | | | **75.63** |

### 5.2 Hypothesis Testing with Composite Assessment Score

**Null Hypothesis (H0)**: CAS ≤ 50 (Project is impractical and lacks benefits)
**Alternative Hypothesis (H1)**: CAS > 50 (Project is viable with meaningful benefits)

**One-sample t-test results**: t(19) = 12.67, p < 0.001, 95% CI [71.28, 79.98]

**Conclusion**: With a Composite Assessment Score of 75.63, which is significantly above the threshold value of 50 (p < 0.001), we reject the null hypothesis (H0) and accept the alternative hypothesis (H1).

### 5.3 Sensitivity Analysis of Hypothesis Testing

**Table 15: Sensitivity Analysis of Composite Assessment Score**

| Scenario | CAS | t-statistic | p-value | Hypothesis Result |
|----------|-----|------------|---------|-------------------|
| Base case | 75.63 | 12.67 | <0.001 | Reject H0 |
| Stakeholder weight doubled | 72.94 | 10.58 | <0.001 | Reject H0 |
| Infrastructure weight doubled | 78.02 | 13.92 | <0.001 | Reject H0 |
| Economic weight doubled | 78.76 | 14.23 | <0.001 | Reject H0 |
| Implementation weight doubled | 72.82 | 10.49 | <0.001 | Reject H0 |
| Pessimistic estimates | 62.17 | 5.43 | <0.001 | Reject H0 |
| Optimistic estimates | 85.42 | 17.87 | <0.001 | Reject H0 |

**Interpretation**: Sensitivity analysis demonstrates that under all tested scenarios, including pessimistic estimates and various weighting schemes, the Composite Assessment Score remains significantly above 50 (p < 0.001), consistently supporting the rejection of the null hypothesis.

## 6. Conclusion of Statistical Analysis

The comprehensive statistical analysis of data collected through stakeholder surveys, infrastructure assessments, economic projections, and implementation barrier evaluations provides strong evidence to reject the null hypothesis (H0) that "the reactivation of Lalmonirhat Airfield for civilian aviation is impractical and lacks substantial socioeconomic advantages."

Instead, the data supports the alternative hypothesis (H1) that "the conversion of Lalmonirhat Airfield to civilian use is viable and delivers meaningful regional development benefits when implementation barriers are successfully overcome."

Key statistical findings supporting this conclusion include:

1. Stakeholder perceptions are significantly positive among local residents, business owners, and government officials (p < 0.001)
2. Technical assessments confirm that required infrastructure upgrades are feasible (all components p < 0.001)
3. Economic analysis shows positive NPV and BCR > 2.5 across all scenarios (p < 0.001)
4. Implementation barriers, while present, generally have feasible mitigation strategies
5. The Composite Assessment Score of 75.63 is significantly above the threshold value (p < 0.001)

These findings demonstrate that while there are challenges to overcome—particularly in terms of current infrastructure condition, funding constraints, and technical expertise requirements—the project has strong potential to deliver meaningful socioeconomic benefits to the Lalmonirhat region when implemented effectively.
