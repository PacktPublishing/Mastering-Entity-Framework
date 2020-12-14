## $5 Tech Unlocked 2021!
[Buy and download this Book for only $5 on PacktPub.com](https://www.packtpub.com/product/mastering-entity-framework/9781784391003)
-----
*If you have read this book, please leave a review on [Amazon.com](https://www.amazon.com/gp/product/178439100X).     Potential readers can then use your unbiased opinion to help them make purchase decisions. Thank you. The $5 campaign         runs from __December 15th 2020__ to __January 13th 2021.__*

#Mastering Entity Framework

This is the code repository for [Mastering Entity Framework](https://www.packtpub.com/application-development/mastering-entity-framework?utm_source=github&utm_medium=repository&utm_campaign=9781784391003), published by Packt. It contains all the supporting project files necessary to work through the book from start to finish.

##Instructions and Navigation
All of the code is organized into folders. Each folder starts with number followed by the application name. For example, 1-GuessTheNumber which is application from chapter 1.

Each Chapter contains lots of code. You will see code something similler to the following:
```
<edmx:ConceptualModels>
	<Schema Namespace="ToDoDBModel" Alias="Self" annotation:UseStrongSpatialTypes="false" xmlns:annotation="http://schemas.microsoft.com/ado/2009/02/edm/annotation" xmlns="http://schemas.microsoft.com/ado/2009/11/edm">
		<EntityType Name="ToDo">
			<Key><PropertyRef Name="Id" /></Key>
			<Property Name="Id" Type="Int32" Nullable="false" />
			<Property Name="TodoItem" Type="String" MaxLength="Max" FixedLength="false" Unicode="true" Nullable="false" />
			<Property Name="IsDone" Type="Boolean" Nullable="false" />
		</EntityType>
		<EntityContainer Name="ToDoDBEntities" annotation:LazyLoadingEnabled="true">
			<EntitySet Name="ToDos" EntityType="Self.ToDo" />
		</EntityContainer>
	</Schema>
</edmx:ConceptualModels>
```
##Related Entity Framework Products:
* [Entity Framework Tutorial](https://www.packtpub.com/application-development/entity-framework-tutorial?utm_source=github&utm_medium=repository&utm_campaign=9781847195227)
* [Entity Framework 4.1: Expert’s Cookbook](https://www.packtpub.com/application-development/entity-framework-41-expert%E2%80%99s-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781849684460)
* [WCF Multi-layer Services Development with Entity Framework - Fourth Edition](https://www.packtpub.com/application-development/wcf-multi-layer-services-development-entity-framework-4th-edition?utm_source=github&utm_medium=repository&utm_campaign=9781784391041)
