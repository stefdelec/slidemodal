# slidemodal
A bootstrap-like modal that opens on sides.


   Code example
   
   
   <!-- Trigger the modal with a button -->
<button type="button" class="btn btn-info btn-lg" data-toggle="sidemodal" data-target="#sidetimeline">Open SideModal</button>

<!-- Modal -->
<div id="sidetimeline" class="sidemodal">
    <!-- Modal content-->
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close"data-dismiss="sidemodal">&times;</button>
        <h4 class="modal-title">Modal Header</h4>
      </div>
      <div class="modal-body">
        <p>Some text in the modal.</p>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
      </div>
    </div>
</div>
