<script>
    import Navbar from "../../template/Navbar.svelte";

    function handler() {
        // @ts-ignore
        let email_subject = encodeURI(document.getElementById("email_subject").value);
        // @ts-ignore
        let email_body = encodeURI(document.getElementById("email_body").value);
        
        if (email_subject.trim() === '' || email_body.trim() === '') {
            alert("Please enter subject and body before clicking send");
            return; // Do not submit the form if either textarea is empty
        }
        
        console.log(email_subject);
        console.log(email_body);
        let emailto = "mailto:harrysharma1066@gmail.com?subject="+email_subject+"&body="+email_body;
        console.log(emailto);
        window.open(emailto);
    }
</script>
<Navbar/>
<div class="h-screen flex flex-col items-center justify-center"> 
    <p class="text-teal-500 text-xl mb-3">Contact me</p> 

    <form on:submit|preventDefault={handler}> 
        <textarea id="email_subject" name="email_subject" aria-label="Enter subject" placeholder="Enter subject ..." class="text-sm text-gray-base w-full mr-3 py-5 px-4 h-[75px] border border-gray-200 rounded mb-2" style="resize: none;"></textarea>
        <textarea id="email_body" name="email_body" aria-label="Enter body" placeholder="Enter body ..." class="text-sm text-gray-base w-full mr-3 py-5 px-4 h-[250px] border border-gray-200 rounded mb-2" style="resize: none;"></textarea>

        <button type="submit" class="bg-teal-500 hover:bg-teal-700 w-full mt-4 rounded mb-2 text-white">Send</button> 
    </form> 
</div>

