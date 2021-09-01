

<!-- PROJECT LOGO -->
<p align="center">
    <h3 align="center">PAIP2020</h3>
    <p align="center">
        PAIP2020 is the second challenge organized by the Pathology AI Platform (PAIP) <br>and the Seoul National University Hospital (SNUH).
    <br>
        <a href="https://paip2020.grand-challenge.org"><strong>PAIP2020 homepage</strong></a>
    </p>      
</p>



<!--Table of Contents--!>

<strong>Table of contents</strong>
<details open="open">
    <ol>

          <li>Images</li>
          <li>Labels_mask</li>
          <li>Labels_xml</li>

    </ol>
</details>



<!--PAIP2020 challenge-->
## Region Aggregated Attention CNN for Disease Detection in Fruit Images

<ul>
    <li>
        <strong>background:</strong>
        <p>Microsatellite instability (MSI), caused by a defective DNA mismatch repair system, has both prognostic and therapeutic implications in colorectal cancer (CRC).MSI is determined by using five microsatellite markers, including D2S123, D5S346, D17S250, BAT25, and BAT26.
        <ul>
            <li>MSI-High (MSI-H; instability at ≥ 2 microsatellite markers)</li>
            <li>MSI-Low (MSI-L; instability at 1 marker)</li>
            <li>MSI-Stable (MSS; microsatellite stable or no instability)</li></ul>
        </p>
    </li>
    <li>
        <strong>dataset</strong></li>
        <p>
           <ul>
                <li>The training dataset contains 47 WSIs</li>
                <li>The validation dataset contains 31 WSIs</li>
                <li>The test dataset contains 40 WSIs</li>
                <p>
                    All WSIs were scanned at 40X magnification and all cases are randomly selected irrespective of the participating institutions.
                </p>
           </ul>
        </p>
    <li>
        <strong>evaluation</strong>
        <ul>
            <li>Evaluation Step #1: MSI prediction accuracy (quantitative assessment)</li>
            <li>Evaluation Step #2: Colorectal tumor segmentation accuracy (qualitative assessment)</li>
        </ul>
    </li>


</ul>
