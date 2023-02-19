# sampling_credit_card
This file gives accuracy score for different sampling techniques(on inbalanced data) trained on different models as given below
<ul>
    <li>
        Sampling Techniques
        <ol>
            <li>
                Under Sampling
            </li>
            <li>
                Over Sampling
            </li>
            <li>
                Tomek links
            </li>
            <li>
                SMOTE
            </li>
            <li>
                Near Miss
            </li>
        </ol>
    </li>
    <li>
        Modelling techniques
        <ol>
            <li>
                XGB
            </li>
            <li>
                Random Forest
            </li>
            <li>
                Decision Tree
            </li>
            <li>
                SVM
            </li>
            <li>
                Naive Bayesian
            </li>
        </ol>
    </li>
</ul>
<h1>Result table</h1>
|<table>
    <tr>
        <td>Model\Sampling</td>
        <td>Under sampling</td>
        <td>Over sampling</td>
        <td>Tomek Links</td>
        <td>SMOTE</td>
        <td>Near Miss</td>
    </tr>
    <tr>
        <td>XGB</td>
        <td>0.625</td>
        <td>0.991817</td>
        <td>0.996732</td>
        <td>0.99509</td>
        <td>0.125</td>
    </tr>
    <tr>
        <td>Random Forest</td>
        <td>0.625</td>
        <td>0.998363</td>
        <td>0.996732</td>
        <td>0.998363</td>
        <td>0.125</td>
    </tr>
    <tr>
        <td>Decision Tree</td>
        <td>0.75</td>
        <td>0.988543</td>
        <td>0.980392</td>
        <td>0.988543</td>
        <td>0.25</td>
    </tr>
    <tr>
        <td>SVM</td>
        <td>0.625</td>
        <td>0.937807</td>
        <td>0.996732</td>
        <td>0.95581</td>
        <td>0.5</td>
    </tr>
    <tr>
        <td>Naïve Bayesian</td>
        <td>0.75</td>
        <td>0.913257</td>
        <td>0.993464</td>
        <td>0.86743</td>
        <td>0.375</td>
    </tr>
</table>

<h3>Note:-accuracy value may be inaccurate or accurate as depicted in first half too</h3>
<h6>For reference, csv file is added into this repo too but in python file its taken from original git link only</h6>
