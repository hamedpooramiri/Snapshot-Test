# Snapshot-Test

Usage: 😎
Use this extension for snapshot testing for your views layout 

  🟢 Create a folder named 'snapshots' adjacent to your swift test file, your snapshots will be saved in that folder
  
  🟢 Use 'assert'/'record' functions to record a snapshot or assert 
  
  🟢 Add snapshots file to Xcode and git repository
  

Record Snapshot: 

  Use the 'record' function to record a snapshot of your ViewController

  
    record(snapshot: anyViewController.snapshot(for: .iPhone8(style: .light)), named: "ANY_SNAPSHOT_NAME")

  Assert Snapshot: 
  
   Use the 'assert' function to assert a snapshot

      
  
    assert(snapshot: anyViewController.snapshot(for: .iPhone8(style: .light)), named: "ANY_SNAPSHOT_NAME")

	
