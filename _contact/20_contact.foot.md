---
language: foot
key: contact
---
<hr clas="mt-0"/>
<form method="post" action="https://formspree.io/formspree@lilybee.ch">
    <div class="row">
        <div class="col-md-6 form-group">
            <label for="namefield">Name</label>
            <input id="namefield" type="text" class="form-control" placeholder="Name" name="name"/>
        </div>
        <div class="col-md-6 form-group">
            <label for="emailfield">Email</label>
            <input id="emailfield" type="email" class="form-control" placeholder="Email" name="_replyto"/>
        </div>
    </div>
    <div class="row">
        <div class="col form-group">
            <input id="subjectfield" type="text" class="form-control" placeholder="Subject" name="_subject" />
        </div>
    </div>
    <div class="row">
        <div class="col form-group">
            <textarea class="form-control" name="message" placeholder="Message" rows="8"></textarea>
        </div>
    </div>
    <div class="row">
        <div class="col">
          <button type="submit" class="btn btn-primary mb-2">Send Message</button>
        </div>
    </div>
    <input type="hidden" name="formurl" value="{{page.url}}" />
    <input type="hidden" name="_next" value="{{site.baseurl}}/submitted.html" />
</form>
