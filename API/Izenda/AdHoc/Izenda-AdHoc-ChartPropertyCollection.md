#ChartPropertyCollection

[[_TOC_]]

##Properties

|Datatype|Property name|Property description|Default Value|
|:-------|:----------:|:-----------------:|:-----------:|
|String[]|[[AllKeys|/API/Izenda/AdHoc/CodeSamples/Izenda_AdHoc_ChartPropertyCollection_AllKeys]]|Returns a [[System.String|http://msdn.microsoft.com/en-us/library/s1wwdcbf]] array that contains all the keys  in the [[Izenda.AdHoc.ChartPropertyCollection|/API/Izenda/AdHoc/Izenda-AdHoc-ChartPropertyCollection]] instance.|[]|
|Array|[[AllValues|/API/Izenda/AdHoc/CodeSamples/Izenda_AdHoc_ChartPropertyCollection_AllValues]]|Returns a [[System.Object|http://msdn.microsoft.com/en-us/library/e5kfa45b]] array that contains all the values  in the [[Izenda.AdHoc.ChartPropertyCollection|/API/Izenda/AdHoc/Izenda-AdHoc-ChartPropertyCollection]] instance.|[]|
|Int32|[[Count|http://msdn.microsoft.com/en-us/library/25705c27]]|Gets the number of key/value pairs contained in the [[System.Collections.Specialized.NameObjectCollectionBase|http://msdn.microsoft.com/en-us/library/ts6a60s4]] instance.|0|
|Boolean|[[HasKeys|/API/Izenda/AdHoc/CodeSamples/Izenda_AdHoc_ChartPropertyCollection_HasKeys]]|Gets a value indicating whether the [[Izenda.AdHoc.ChartPropertyCollection|/API/Izenda/AdHoc/Izenda-AdHoc-ChartPropertyCollection]] instance  contains entries whose keys are not a null reference .|False|
|ChartProperty|[[Item|/API/Izenda/AdHoc/CodeSamples/Izenda_AdHoc_ChartPropertyCollection_Item_-_System_String_-_]]|Gets the [[Izenda.AdHoc.ChartProperty|/API/Izenda/AdHoc/Izenda-AdHoc-ChartProperty]] using the specified [[System.String|http://msdn.microsoft.com/en-us/library/s1wwdcbf]] key.|null|
|KeysCollection|[[Keys|http://msdn.microsoft.com/en-us/library/s4tkstha]]|Gets a [[System.Collections.Specialized.KeysCollection|http://msdn.microsoft.com/en-us/library/w37hzh9w]] instance that contains all the keys in the [[System.Collections.Specialized.NameObjectCollectionBase|http://msdn.microsoft.com/en-us/library/ts6a60s4]] instance.|{}|


##Methods

###Add(System.String,Izenda.AdHoc.ChartProperty)
Adds an entry with the specified key and value into the [[Izenda.AdHoc.ChartPropertyCollection|/API/Izenda/AdHoc/Izenda-AdHoc-ChartPropertyCollection]] instance.

Parameters: 

* [[System.String|http://msdn.microsoft.com/en-us/library/s1wwdcbf]] key  - The [[System.String|http://msdn.microsoft.com/en-us/library/s1wwdcbf]] key of the entry to add.
* [[Izenda.AdHoc.ChartProperty|/API/Izenda/AdHoc/Izenda-AdHoc-ChartProperty]] value  - The [[Izenda.AdHoc.ChartProperty|/API/Izenda/AdHoc/Izenda-AdHoc-ChartProperty]] value of the entry to add.






---


###Clear()
Removes all entries from the [[Izenda.AdHoc.ChartPropertyCollection|/API/Izenda/AdHoc/Izenda-AdHoc-ChartPropertyCollection]] instance.






---


###Contains(System.String)
Determines whether the [[Izenda.AdHoc.ChartPropertyCollection|/API/Izenda/AdHoc/Izenda-AdHoc-ChartPropertyCollection]] contains the specified [[System.String|http://msdn.microsoft.com/en-us/library/s1wwdcbf]] key.

Parameters: 

* [[System.String|http://msdn.microsoft.com/en-us/library/s1wwdcbf]] key  - The [[System.String|http://msdn.microsoft.com/en-us/library/s1wwdcbf]] key to check for.






---


###Equals(System.Object)
Determines whether the specified [[System.Object|http://msdn.microsoft.com/en-us/library/e5kfa45b]] is equal to the current [[System.Object|http://msdn.microsoft.com/en-us/library/e5kfa45b]].

Parameters: 

* [[System.Object|http://msdn.microsoft.com/en-us/library/e5kfa45b]] obj  - The [[System.Object|http://msdn.microsoft.com/en-us/library/e5kfa45b]] to compare with the current [[System.Object|http://msdn.microsoft.com/en-us/library/e5kfa45b]].





Returns:

true if the specified [[System.Object|http://msdn.microsoft.com/en-us/library/e5kfa45b]] is equal to the current System.Object; otherwise, false.


---


###GetEnumerator()
Returns an enumerator that iterates through the [[System.Collections.Specialized.NameObjectCollectionBase|http://msdn.microsoft.com/en-us/library/ts6a60s4]].





Returns:

An [[System.Collections.IEnumerator|http://msdn.microsoft.com/en-us/library/1t2267t6]] for the [[System.Collections.Specialized.NameObjectCollectionBase|http://msdn.microsoft.com/en-us/library/ts6a60s4]] instance.


---


###GetHashCode()
 Serves as a hash function for a particular type.  





Returns:

A hash code for the current [[System.Object|http://msdn.microsoft.com/en-us/library/e5kfa45b]].


---


###GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)
Implements the [[System.Runtime.Serialization.ISerializable|http://msdn.microsoft.com/en-us/library/wf4375ks]] interface and returns the data needed to serialize the [[System.Collections.Specialized.NameObjectCollectionBase|http://msdn.microsoft.com/en-us/library/ts6a60s4]] instance.

Parameters: 

* [[System.Runtime.Serialization.SerializationInfo|http://msdn.microsoft.com/en-us/library/a9b6042e]] info  - A [[System.Runtime.Serialization.SerializationInfo|http://msdn.microsoft.com/en-us/library/a9b6042e]] object that contains the information required to serialize the [[System.Collections.Specialized.NameObjectCollectionBase|http://msdn.microsoft.com/en-us/library/ts6a60s4]] instance.
* [[System.Runtime.Serialization.StreamingContext|http://msdn.microsoft.com/en-us/library/t16abws5]] context  - A [[System.Runtime.Serialization.StreamingContext|http://msdn.microsoft.com/en-us/library/t16abws5]] object that contains the source and destination of the serialized stream associated with the [[System.Collections.Specialized.NameObjectCollectionBase|http://msdn.microsoft.com/en-us/library/ts6a60s4]] instance.






---


###GetType()
Gets the [[System.Type|http://msdn.microsoft.com/en-us/library/42892f65]] of the current instance.





Returns:

The [[System.Type|http://msdn.microsoft.com/en-us/library/42892f65]] instance that represents the exact runtime type of the current instance.


---


###OnDeserialization(System.Object)
Implements the [[System.Runtime.Serialization.ISerializable|http://msdn.microsoft.com/en-us/library/wf4375ks]] interface and raises the deserialization event when the deserialization is complete.

Parameters: 

* [[System.Object|http://msdn.microsoft.com/en-us/library/e5kfa45b]] sender  -  The source of the deserialization event. 






---


###Remove(System.String)
Removes the entries with the specified key from the [[Izenda.AdHoc.ChartPropertyCollection|/API/Izenda/AdHoc/Izenda-AdHoc-ChartPropertyCollection]] instance.

Parameters: 

* [[System.String|http://msdn.microsoft.com/en-us/library/s1wwdcbf]] key  - The [[System.String|http://msdn.microsoft.com/en-us/library/s1wwdcbf]] key of the entries to remove.






---


###Remove(System.Int32)
Removes the entry at the specified index of the [[Izenda.AdHoc.ChartPropertyCollection|/API/Izenda/AdHoc/Izenda-AdHoc-ChartPropertyCollection]] instance.

Parameters: 

* [[System.Int32|http://msdn.microsoft.com/en-us/library/td2s409d]] index  - The zero-based index of the entry to remove.






---


###ToString()
Returns a [[System.String|http://msdn.microsoft.com/en-us/library/s1wwdcbf]] that represents the current [[System.Object|http://msdn.microsoft.com/en-us/library/e5kfa45b]].





Returns:

A [[System.String|http://msdn.microsoft.com/en-us/library/s1wwdcbf]] that represents the current [[System.Object|http://msdn.microsoft.com/en-us/library/e5kfa45b]].


---

