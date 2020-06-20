% Please add the following required packages to your document preamble:
% \usepackage{multirow}
\begin{table}[]
\begin{tabular}{ccll}
Package               & Purpose                                            & \multicolumn{1}{c}{Method}                                                                                                                                  & \multicolumn{1}{c}{Function} \\
\multirow{14}{*}{pwr} & \multirow{4}{*}{Effect Size Calculation}           & Calculate the conventional effect size for the tests                                                                                                        & cohen.ES                     \\
                      &                                                    & Chi-squared test of goodness of test for two sets of  k probabilities                                                                                       & ES.w1                        \\
                      &                                                    & Chi-squared test of association for two-way   contingency                                                                                                   & ES.w2                        \\
                      &                                                    & Two proportions test                                                                                                                                        & ES.h                         \\
                      & \multirow{10}{*}{Sample Size or Power Calculation} & One proportion test                                                                                                                                         & pwr.p.test                   \\
                      &                                                    & Two proportions test with same sample size                                                                                                                  & pwr.2p.test                  \\
                      &                                                    & Two proportions test with different sample size                                                                                                             & pwr.2p2n.test                \\
                      &                                                    & \multirow{2}{*}{\begin{tabular}[c]{@{}l@{}}T-test \\  1. one sample\\  2. two independent samples with same sample   size\\  3. paired sample\end{tabular}} & \multirow{2}{*}{pwr.t.test}  \\
                      &                                                    &                                                                                                                                                             &                              \\
                      &                                                    & T-test: two independent samples with different sample   size                                                                                                & pwr.t2n.test                 \\
                      &                                                    & Balanced ANOVA                                                                                                                                              & pwr.anova.test               \\
                      &                                                    & Correlation test                                                                                                                                            & pwr.r.test                   \\
                      &                                                    & Chi-squared test                                                                                                                                            & pwr.chisq.test               \\
                      &                                                    & General linear model                                                                                                                                        & pwr.f2.test                 
\end{tabular}
\end{table}
