# Bioimage analysis best practices

## Plan your assay

Plan your assay, including sample preparation, microscopy, image analysis, statistical and data analysis, ideally with a team of experts.

For example, certain measurements in images can only be performed if the microscopy meets corresponding requirements on spatial and temporal resolution.

## Establish your workflow with few representative samples

Establish your workflow with a minimal set of samples, ideally showing obvious and biologically relevant differences. 
Visually inspecting these samples will provide invaluable guidance for designing a relevant image analysis pipeline.
Typically, you will also learn how to further optimise 
sample preperation and microscopy such that relevant biological parameters are optimally captured.

(Without samples showing relevant differences it can be very difficult to know which aspects 
of image acquisition and analysis to focus on.)

## Always include controls

It is strongly recommended to always include controls (negative and positive) into your assay. 
Good controls show visually obvious and biologically relevant differences. 
Negative controls are very important for normalisation of the data. 

## Perform regular quality control

When you image and analyse many samples, unanticipated phenotypes (and artefacts) can occur 
and may cause the image analysis to fail. Thus, you must regularly check the image analysis output. 
Typically, the image analysis pipeline needs to be optimised several times in order to 
properly handle all the phentotypes that can occur in your experiment.

## Mind your image acquisition modalities

Changing your image acquisition modalities (e.g. changing magnification) will almost certainly cause your image analysis to fail.
Thus, you must know for which input data your analysis pipeline was made. To ensure this, it is strongly 
recommended to keep your analysis_pipeline_file together with other important information as shown below:

- analysis_folder
    - analysis_pipeline_file
    - image_acquisition_settings_text_file
    - example_input_data_folder
        - negative_control_example_image_file
        - positive_control_example_image_file
    - example_results_folder
        - results_file(s)  

## Report image analysis accuracy in talks and publications

When you present your work you have to report on the accuracy of the image analysis pipeline. 
Typically, this will mean to compare the automated analysis results to a representative subset of manually analysed images.
It is best practice to have several (e.g. three) persons perform the manual analysis and discuss potential disagreements.

