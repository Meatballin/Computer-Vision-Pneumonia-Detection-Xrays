<main>
    <div>
        <h1>Welcome to team The Incredibles Pneumonia Severity Detection</h1>
        <div>
            <h2>How to Run:</h2>
            <div>
                <p>1. Make sure to have Python v3.9 and to check the "requirements.txt" folder for compatibility installations </p>
                </code></pre>
            </div>
            <div>
                <p>2.Navigate your way to the ./code/ directory and open the "dataSplitting" folder. Inside here is where you will obtain one split of data(before conversions to numpy arrays happen). Open the "Readme" file and follow instructions 1 - 5.  </p>
                </code></pre>
            </div>
            <div>
                <p>3. Once a split of data is complete and inside the directory ./dataSplitting/, run through the entire Jupyter Source File called "converting". This will convert the split from step 1 into numpy arrays and the proper data types before being ran through the model.
                NOTE: This process will take about 40 minutes - 1 hour to complete. </p>
                </code></pre>
            </div>
            <div>
                <p>4. Once "converting" is complete, there will be 4 files present in the ./dataSplitting/ directory. They will be called: <br><br>
                <pre><code>
                1)  test_image_arrays.npy
                2)  test_labels.npy
                3)  train_image_arrays.npy
                4)  train_labels.npy 
                </code></pre>
            </div>
            <div>
                <p> 4)  Drag these 4 numpy files into the directory called ./code/</p>
            </div>
            <div>
                <p> 5) Run through the Jupyter Source File named "final" inside of ./code. This file will load those 4 numpy files and pre-process the images before running through the model. </p>
            </div>
            <div>
                <p> 6) Once "final" has been run, you have successfuly completed one split of data. The model will save the weights. </p>
            </div>
            <div>
                <p> 7) Delete the 4 numpy files from the ./code/ directory and from the ./dataSplitting/ directory. Also, delete the folder called "split" that appeared after completing step 1). </p>
            </div>
            <div>
                <p> 8) Repeat step 2 through step 7 nine more times to fully train the model and obtain high validation accuracy. </p>
            </div>
                <p>
                Here is a video presentation of our project: <br>
                https://www.youtube.com/watch?v=OJhiQaDeXlI
                </p>
            </div>   
        </div>
    </div>
</main>



