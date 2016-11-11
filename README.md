# VIPER PLYOM TEMPLATE


A simple template to a VIPER based files. 

Recommended Architecture: 

-- Module
---- BusinessLogic
-------- Interactor
------------ ModuleInteractor.swift
------------ ModuleInteractorInput.swift
------------ ModuleInteractorOutput.swift
-------- Manager
------------ ModuleManager.swift
---- User Interface
-------- View
------------ ModuleViewController.swift
------------ ModuleViewInterface.swift
-------- Presenter
------------ ModulePresenter.swift
-------- Router
------------ ModuleRouter.swift
