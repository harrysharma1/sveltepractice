<script>
    import Navbar from "../../template/Navbar.svelte";
    let encodedString = "mailto:harrysharma1066@gmail.com?subject=test_subject&body=test_body";
    let emailSubject = "";
    let emailBody = "";
    
    function updateEncodedString() {
        encodedString = `mailto:harrysharma1066@gmail.com?subject=${encodeURIComponent(emailSubject)}&body=${encodeURIComponent(emailBody)}`;
    }
</script>
<Navbar/>
<div class="h-screen flex flex-col  
items-center justify-center"> 
<p class="text-teal-500 text-xl mb-3"> 
Contact
</p> 

<form on:submit|preventDefault={updateEncodedString}> 

<textarea bind:value={emailSubject} id="email_subject" aria-label="Enter subject" placeholder="Enter subject ..." class="text-sm text-gray-base w-full mr-3  py-5 px-4 h-[75px] border border-gray-200  rounded mb-2" style="resize: none;"></textarea>
<textarea bind:value={emailBody} id="email_body" aria-label="Enter body" placeholder="Enter body ..." class="text-sm text-gray-base w-full mr-3  py-5 px-4 h-[250px] border border-gray-200  rounded mb-2" style="resize: none;"></textarea>

<button type="submit"
    class="bg-teal-500 hover:bg-teal-700 w-full mt-4 rounded mb-2 text-white"> 
Send 
</button> 
</form> 
</div>

