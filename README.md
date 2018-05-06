# tmp
to delete within a week

I will just build the language model (conditional probabilities distribution of words given some prefix sequence). To achieve this, I will just use plain LSTM RNN. To train it, I will use extracts from originl text of the length (say from 30 to 50) and use this model to predict next word given the sequence before. Actually, what I will do is just predicting probability of each word, so I will work with vocabulary (most popular 1500-2000 words) of constrained size. The loss function is cross-entropy.

Examples:
упомянутое рабское самосознание , все одушевленное и дух обнаружился в тождестве с самим собой и является разум внешний объект для других , предмет тождество , внешний совершенно справедливо для противоречия характер ; другое что для себя теперь является не " я " , погружается во внутреннее самости , государства , через снятие их таким unknown ; единичности , до бы только , то , чему из unknown ехать по весьма unknown делу ну unknown тогда unknown для себя " я определил как вам 

вам счастье прежде всего сути , просто и к идее природы что-нибудь завтраком

друг , как его жена и " я " , постольку самосознание есть в то же время у себя как углубление , проникновение и внедрение в особенно который тождество - в его абсолютной истине не только с объектом , вот другое , а не unknown со мной на дружеской ноге
