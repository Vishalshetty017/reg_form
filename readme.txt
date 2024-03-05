mongoose.connect(`mongodb+srv://${username}:${password}@cluster0.7f6rvjx.mongodb.net`, {
    useNewUrlParser: true,
    useUnifiedTopology: true,
});
mongoose.connect(`mongodb+srv://${username}:${password}@cluster0.7f6rvjx.mongodb.net/mongodb://localhost:27017`,{
    useNewUrlParser : true,
    useUnifiedTopology : true,
});