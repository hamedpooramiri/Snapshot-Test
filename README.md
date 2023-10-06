# Snapshot-Test

Usage:
use this extension for snapshot testing for your view layout 

  1- create a folder named 'snapshots' adjacent to your swift test file, your snapshots will be saved in that folder
  
  2- use assert/record functions to record a snapshot or assert 
  
  3- add snapshots file to Xcode and git repository
  

Record Snapshot: 
      use the 'record' function to record a snapshot of your ViewController

  
    record(snapshot: anyViewController.snapshot(for: .iPhone8(style: .light)), named: "ANY_SNAPSHOT_NAME")

  Assert Snapshot: 
      use the 'assert' function to assert a snapshot

      
  
    assert(snapshot: anyViewController.snapshot(for: .iPhone8(style: .light)), named: "ANY_SNAPSHOT_NAME")

	
