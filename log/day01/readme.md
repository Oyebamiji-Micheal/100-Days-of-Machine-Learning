# 100 Days of Pure and Applied Machine Learning
## Day 01: The Machine Learning Landscape

<hr />

<p align="center">
  <img src="https://github.com/Oyebamiji-Micheal/100-Days-of-Machine-Learning/blob/main/log/day01/images/intro_to_ml.jpg">
</p>

Welcome to day 01 of machine learning! Today, I read the first chapter of the book <strong>Hands-On Machine Learning with Scikit-Learn, Keras and Tensorflow by Aurelien Geron</strong>. Here is a summary of what I noted

<ul>
	<li>
		The first ML application that really became mainstream, improving the lives of hundreds of millions of people, took over the world back in the 1990s: the spam filter
    </li>
	<li>
		Machine learning is the field of study that gives computers the ability to learn without being explicitly programmed. — Arthur Samuel, 1959
	</li>
		Digging into large amounts of data to discover hidden patterns is called *data mining*
	</li>
</ul>

<br />

<strong>Applications of machine learning include</strong>
    <ul>
        <li>
            <strong>Detecting tumors in brain scans:</strong> This is semantic image segmentation, where each pixel in the image is classified (as we want to determine the exact location and shape of tumors), typically using CNNs or transformers
        </li>
        <li>
            <strong>Automatically classifying news articles:</strong> This is natural language processing (NLP), and more specifically text classification, which can be tackled using recurrent neural networks (RNNs) and CNNs, but transformers work even better
        </li>
        <li>
            <strong>Voice recognition or commands in app:</strong> They are typically processed using RNNs, CNNs, or transformers
        </li>
    </ul>
</li>

<br />

<strong>Types of machine learning system</strong>
    <ul>
        <li>
            <strong>Training Supervision:</strong> ML systems can be classified according to the amount and type of supervision they get during training. Examples include supervised learning, unsupervised learning, self-supervised learning, semi-supervised learning, and reinforcement learning.
        </li>
        <li>
            <strong>Batch Versus Online learning: </strong>Another criterion used to classify machine learning systems is whether or not the system can learn incrementally from a stream of incoming data.  
        </li>
        <li>
            <strong>Voice recognition or commands in app:</strong> They are typically processed using RNNs, CNNs, or transformers
        </li>
    </ul>
</li>

<br />

<strong>Additional Keypoins</strong>
- A model’s performance tends to decay slowly over time, simply because the world continues to evolve while the model remains unchanged. This phenomenon is often called model rot or data drift.

- It is crucial to use a training set that is representative of the cases you want to generalize to. This is often harder than it sounds: if the sample is too small, you will have sampling noise (i.e., nonrepresentative data as a result of chance), but even very large samples can be nonrepresentative if the sampling method is flawed. This is called sampling bias.

- Overfitting happens when the model is too complex relative to the amount and noisiness of the training data.

- Constraining a model to make it simpler and reduce the risk of overfitting is called regularization.

- The amount of regularization to apply during learning can be controlled by a hyperparameter.

- Underfitting it occurs when your model is too simple to learn the underlying structure of the data.


