let sdk = new Appwrite();

sdk
    setProject('')
;

let promise = sdk.projects.updateKey('[PROJECT_ID]', '[KEY_ID]', '[NAME]', []);

promise.then(function (response) {
    console.log(response);
}, function (error) {
    console.log(error);
});