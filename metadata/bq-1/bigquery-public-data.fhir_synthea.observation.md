# `fhir_synthea.observation`
`bigquery`| `bigquery-public-data`

## Column details
* [RECORD]    `basedOn`
* [STRING]    `basedOn.carePlanId`
* [STRING]    `basedOn.deviceRequestId`
* [STRING]    `basedOn.immunizationRecommendationId`
* [STRING]    `basedOn.medicationRequestId`
* [STRING]    `basedOn.nutritionOrderId`
* [STRING]    `basedOn.procedureRequestId`
* [STRING]    `basedOn.referralRequestId`
* [STRING]    `basedOn.reference`
* [RECORD]    `basedOn.identifier`
* [STRING]    `basedOn.identifier.use`
* [RECORD]    `basedOn.identifier.type`
* [RECORD]    `basedOn.identifier.type.coding`
* [STRING]    `basedOn.identifier.type.coding.system`
* [STRING]    `basedOn.identifier.type.coding.version`
* [STRING]    `basedOn.identifier.type.coding.code`
* [STRING]    `basedOn.identifier.type.coding.display`
* [BOOLEAN]   `basedOn.identifier.type.coding.userSelected`
* [STRING]    `basedOn.identifier.type.text`
* [STRING]    `basedOn.identifier.system`
* [STRING]    `basedOn.identifier.value`
* [RECORD]    `basedOn.identifier.period`
* [STRING]    `basedOn.identifier.period.start`
* [STRING]    `basedOn.identifier.period.end`
* [RECORD]    `basedOn.identifier.assigner`
* [STRING]    `basedOn.identifier.assigner.organizationId`
* [STRING]    `basedOn.identifier.assigner.reference`
* [RECORD]    `basedOn.identifier.assigner.identifier`
* [STRING]    `basedOn.identifier.assigner.identifier.use`
* [RECORD]    `basedOn.identifier.assigner.identifier.type`
* [RECORD]    `basedOn.identifier.assigner.identifier.type.coding`
* [STRING]    `basedOn.identifier.assigner.identifier.type.coding.system`
* [STRING]    `basedOn.identifier.assigner.identifier.type.coding.version`
* [STRING]    `basedOn.identifier.assigner.identifier.type.coding.code`
* [STRING]    `basedOn.identifier.assigner.identifier.type.coding.display`
* [BOOLEAN]   `basedOn.identifier.assigner.identifier.type.coding.userSelected`
* [STRING]    `basedOn.identifier.assigner.identifier.type.text`
* [STRING]    `basedOn.identifier.assigner.identifier.system`
* [STRING]    `basedOn.identifier.assigner.identifier.value`
* [RECORD]    `basedOn.identifier.assigner.identifier.period`
* [STRING]    `basedOn.identifier.assigner.identifier.period.start`
* [STRING]    `basedOn.identifier.assigner.identifier.period.end`
* [RECORD]    `basedOn.identifier.assigner.identifier.assigner`
* [STRING]    `basedOn.identifier.assigner.identifier.assigner.organizationId`
* [STRING]    `basedOn.identifier.assigner.identifier.assigner.reference`
* [STRING]    `basedOn.identifier.assigner.identifier.assigner.display`
* [STRING]    `basedOn.identifier.assigner.display`
* [STRING]    `basedOn.display`
* [RECORD]    `bodySite`
* [RECORD]    `bodySite.coding`
* [STRING]    `bodySite.coding.system`
* [STRING]    `bodySite.coding.version`
* [STRING]    `bodySite.coding.code`
* [STRING]    `bodySite.coding.display`
* [BOOLEAN]   `bodySite.coding.userSelected`
* [STRING]    `bodySite.text`
* [STRING]    `comment`
* [RECORD]    `dataAbsentReason`
* [RECORD]    `dataAbsentReason.coding`
* [STRING]    `dataAbsentReason.coding.system`
* [STRING]    `dataAbsentReason.coding.version`
* [STRING]    `dataAbsentReason.coding.code`
* [STRING]    `dataAbsentReason.coding.display`
* [BOOLEAN]   `dataAbsentReason.coding.userSelected`
* [STRING]    `dataAbsentReason.text`
* [RECORD]    `device`
* [STRING]    `device.deviceId`
* [STRING]    `device.deviceMetricId`
* [STRING]    `device.reference`
* [RECORD]    `device.identifier`
* [STRING]    `device.identifier.use`
* [RECORD]    `device.identifier.type`
* [RECORD]    `device.identifier.type.coding`
* [STRING]    `device.identifier.type.coding.system`
* [STRING]    `device.identifier.type.coding.version`
* [STRING]    `device.identifier.type.coding.code`
* [STRING]    `device.identifier.type.coding.display`
* [BOOLEAN]   `device.identifier.type.coding.userSelected`
* [STRING]    `device.identifier.type.text`
* [STRING]    `device.identifier.system`
* [STRING]    `device.identifier.value`
* [RECORD]    `device.identifier.period`
* [STRING]    `device.identifier.period.start`
* [STRING]    `device.identifier.period.end`
* [RECORD]    `device.identifier.assigner`
* [STRING]    `device.identifier.assigner.organizationId`
* [STRING]    `device.identifier.assigner.reference`
* [RECORD]    `device.identifier.assigner.identifier`
* [STRING]    `device.identifier.assigner.identifier.use`
* [RECORD]    `device.identifier.assigner.identifier.type`
* [RECORD]    `device.identifier.assigner.identifier.type.coding`
* [STRING]    `device.identifier.assigner.identifier.type.coding.system`
* [STRING]    `device.identifier.assigner.identifier.type.coding.version`
* [STRING]    `device.identifier.assigner.identifier.type.coding.code`
* [STRING]    `device.identifier.assigner.identifier.type.coding.display`
* [BOOLEAN]   `device.identifier.assigner.identifier.type.coding.userSelected`
* [STRING]    `device.identifier.assigner.identifier.type.text`
* [STRING]    `device.identifier.assigner.identifier.system`
* [STRING]    `device.identifier.assigner.identifier.value`
* [RECORD]    `device.identifier.assigner.identifier.period`
* [STRING]    `device.identifier.assigner.identifier.period.start`
* [STRING]    `device.identifier.assigner.identifier.period.end`
* [RECORD]    `device.identifier.assigner.identifier.assigner`
* [STRING]    `device.identifier.assigner.identifier.assigner.organizationId`
* [STRING]    `device.identifier.assigner.identifier.assigner.reference`
* [STRING]    `device.identifier.assigner.identifier.assigner.display`
* [STRING]    `device.identifier.assigner.display`
* [STRING]    `device.display`
* [RECORD]    `identifier`
* [STRING]    `identifier.use`
* [RECORD]    `identifier.type`
* [RECORD]    `identifier.type.coding`
* [STRING]    `identifier.type.coding.system`
* [STRING]    `identifier.type.coding.version`
* [STRING]    `identifier.type.coding.code`
* [STRING]    `identifier.type.coding.display`
* [BOOLEAN]   `identifier.type.coding.userSelected`
* [STRING]    `identifier.type.text`
* [STRING]    `identifier.system`
* [STRING]    `identifier.value`
* [RECORD]    `identifier.period`
* [STRING]    `identifier.period.start`
* [STRING]    `identifier.period.end`
* [RECORD]    `identifier.assigner`
* [STRING]    `identifier.assigner.organizationId`
* [STRING]    `identifier.assigner.reference`
* [RECORD]    `identifier.assigner.identifier`
* [STRING]    `identifier.assigner.identifier.use`
* [RECORD]    `identifier.assigner.identifier.type`
* [RECORD]    `identifier.assigner.identifier.type.coding`
* [STRING]    `identifier.assigner.identifier.type.coding.system`
* [STRING]    `identifier.assigner.identifier.type.coding.version`
* [STRING]    `identifier.assigner.identifier.type.coding.code`
* [STRING]    `identifier.assigner.identifier.type.coding.display`
* [BOOLEAN]   `identifier.assigner.identifier.type.coding.userSelected`
* [STRING]    `identifier.assigner.identifier.type.text`
* [STRING]    `identifier.assigner.identifier.system`
* [STRING]    `identifier.assigner.identifier.value`
* [RECORD]    `identifier.assigner.identifier.period`
* [STRING]    `identifier.assigner.identifier.period.start`
* [STRING]    `identifier.assigner.identifier.period.end`
* [RECORD]    `identifier.assigner.identifier.assigner`
* [STRING]    `identifier.assigner.identifier.assigner.organizationId`
* [STRING]    `identifier.assigner.identifier.assigner.reference`
* [STRING]    `identifier.assigner.identifier.assigner.display`
* [STRING]    `identifier.assigner.display`
* [STRING]    `implicitRules`
* [RECORD]    `interpretation`
* [RECORD]    `interpretation.coding`
* [STRING]    `interpretation.coding.system`
* [STRING]    `interpretation.coding.version`
* [STRING]    `interpretation.coding.code`
* [STRING]    `interpretation.coding.display`
* [BOOLEAN]   `interpretation.coding.userSelected`
* [STRING]    `interpretation.text`
* [STRING]    `language`
* [RECORD]    `method`
* [RECORD]    `method.coding`
* [STRING]    `method.coding.system`
* [STRING]    `method.coding.version`
* [STRING]    `method.coding.code`
* [STRING]    `method.coding.display`
* [BOOLEAN]   `method.coding.userSelected`
* [STRING]    `method.text`
* [RECORD]    `performer`
* [STRING]    `performer.practitionerId`
* [STRING]    `performer.organizationId`
* [STRING]    `performer.patientId`
* [STRING]    `performer.relatedPersonId`
* [STRING]    `performer.reference`
* [RECORD]    `performer.identifier`
* [STRING]    `performer.identifier.use`
* [RECORD]    `performer.identifier.type`
* [RECORD]    `performer.identifier.type.coding`
* [STRING]    `performer.identifier.type.coding.system`
* [STRING]    `performer.identifier.type.coding.version`
* [STRING]    `performer.identifier.type.coding.code`
* [STRING]    `performer.identifier.type.coding.display`
* [BOOLEAN]   `performer.identifier.type.coding.userSelected`
* [STRING]    `performer.identifier.type.text`
* [STRING]    `performer.identifier.system`
* [STRING]    `performer.identifier.value`
* [RECORD]    `performer.identifier.period`
* [STRING]    `performer.identifier.period.start`
* [STRING]    `performer.identifier.period.end`
* [RECORD]    `performer.identifier.assigner`
* [STRING]    `performer.identifier.assigner.organizationId`
* [STRING]    `performer.identifier.assigner.reference`
* [RECORD]    `performer.identifier.assigner.identifier`
* [STRING]    `performer.identifier.assigner.identifier.use`
* [RECORD]    `performer.identifier.assigner.identifier.type`
* [RECORD]    `performer.identifier.assigner.identifier.type.coding`
* [STRING]    `performer.identifier.assigner.identifier.type.coding.system`
* [STRING]    `performer.identifier.assigner.identifier.type.coding.version`
* [STRING]    `performer.identifier.assigner.identifier.type.coding.code`
* [STRING]    `performer.identifier.assigner.identifier.type.coding.display`
* [BOOLEAN]   `performer.identifier.assigner.identifier.type.coding.userSelected`
* [STRING]    `performer.identifier.assigner.identifier.type.text`
* [STRING]    `performer.identifier.assigner.identifier.system`
* [STRING]    `performer.identifier.assigner.identifier.value`
* [RECORD]    `performer.identifier.assigner.identifier.period`
* [STRING]    `performer.identifier.assigner.identifier.period.start`
* [STRING]    `performer.identifier.assigner.identifier.period.end`
* [RECORD]    `performer.identifier.assigner.identifier.assigner`
* [STRING]    `performer.identifier.assigner.identifier.assigner.organizationId`
* [STRING]    `performer.identifier.assigner.identifier.assigner.reference`
* [STRING]    `performer.identifier.assigner.identifier.assigner.display`
* [STRING]    `performer.identifier.assigner.display`
* [STRING]    `performer.display`
* [RECORD]    `referenceRange`
* [RECORD]    `referenceRange.low`
* [FLOAT]     `referenceRange.low.value`
* [STRING]    `referenceRange.low.unit`
* [STRING]    `referenceRange.low.system`
* [STRING]    `referenceRange.low.code`
* [RECORD]    `referenceRange.high`
* [FLOAT]     `referenceRange.high.value`
* [STRING]    `referenceRange.high.unit`
* [STRING]    `referenceRange.high.system`
* [STRING]    `referenceRange.high.code`
* [RECORD]    `referenceRange.type`
* [RECORD]    `referenceRange.type.coding`
* [STRING]    `referenceRange.type.coding.system`
* [STRING]    `referenceRange.type.coding.version`
* [STRING]    `referenceRange.type.coding.code`
* [STRING]    `referenceRange.type.coding.display`
* [BOOLEAN]   `referenceRange.type.coding.userSelected`
* [STRING]    `referenceRange.type.text`
* [RECORD]    `referenceRange.appliesTo`
* [RECORD]    `referenceRange.appliesTo.coding`
* [STRING]    `referenceRange.appliesTo.coding.system`
* [STRING]    `referenceRange.appliesTo.coding.version`
* [STRING]    `referenceRange.appliesTo.coding.code`
* [STRING]    `referenceRange.appliesTo.coding.display`
* [BOOLEAN]   `referenceRange.appliesTo.coding.userSelected`
* [STRING]    `referenceRange.appliesTo.text`
* [RECORD]    `referenceRange.age`
* [RECORD]    `referenceRange.age.low`
* [FLOAT]     `referenceRange.age.low.value`
* [STRING]    `referenceRange.age.low.unit`
* [STRING]    `referenceRange.age.low.system`
* [STRING]    `referenceRange.age.low.code`
* [RECORD]    `referenceRange.age.high`
* [FLOAT]     `referenceRange.age.high.value`
* [STRING]    `referenceRange.age.high.unit`
* [STRING]    `referenceRange.age.high.system`
* [STRING]    `referenceRange.age.high.code`
* [STRING]    `referenceRange.text`
* [RECORD]    `related`
* [STRING]    `related.type`
* [RECORD]    `related.target`
* [STRING]    `related.target.observationId`
* [STRING]    `related.target.questionnaireResponseId`
* [STRING]    `related.target.sequenceId`
* [STRING]    `related.target.reference`
* [RECORD]    `related.target.identifier`
* [STRING]    `related.target.identifier.use`
* [RECORD]    `related.target.identifier.type`
* [RECORD]    `related.target.identifier.type.coding`
* [STRING]    `related.target.identifier.type.coding.system`
* [STRING]    `related.target.identifier.type.coding.version`
* [STRING]    `related.target.identifier.type.coding.code`
* [STRING]    `related.target.identifier.type.coding.display`
* [BOOLEAN]   `related.target.identifier.type.coding.userSelected`
* [STRING]    `related.target.identifier.type.text`
* [STRING]    `related.target.identifier.system`
* [STRING]    `related.target.identifier.value`
* [RECORD]    `related.target.identifier.period`
* [STRING]    `related.target.identifier.period.start`
* [STRING]    `related.target.identifier.period.end`
* [RECORD]    `related.target.identifier.assigner`
* [STRING]    `related.target.identifier.assigner.organizationId`
* [STRING]    `related.target.identifier.assigner.reference`
* [RECORD]    `related.target.identifier.assigner.identifier`
* [STRING]    `related.target.identifier.assigner.identifier.use`
* [RECORD]    `related.target.identifier.assigner.identifier.type`
* [RECORD]    `related.target.identifier.assigner.identifier.type.coding`
* [STRING]    `related.target.identifier.assigner.identifier.type.coding.system`
* [STRING]    `related.target.identifier.assigner.identifier.type.coding.version`
* [STRING]    `related.target.identifier.assigner.identifier.type.coding.code`
* [STRING]    `related.target.identifier.assigner.identifier.type.coding.display`
* [BOOLEAN]   `related.target.identifier.assigner.identifier.type.coding.userSelected`
* [STRING]    `related.target.identifier.assigner.identifier.type.text`
* [STRING]    `related.target.identifier.assigner.identifier.system`
* [STRING]    `related.target.identifier.assigner.identifier.value`
* [RECORD]    `related.target.identifier.assigner.identifier.period`
* [STRING]    `related.target.identifier.assigner.identifier.period.start`
* [STRING]    `related.target.identifier.assigner.identifier.period.end`
* [RECORD]    `related.target.identifier.assigner.identifier.assigner`
* [STRING]    `related.target.identifier.assigner.identifier.assigner.organizationId`
* [STRING]    `related.target.identifier.assigner.identifier.assigner.reference`
* [STRING]    `related.target.identifier.assigner.identifier.assigner.display`
* [STRING]    `related.target.identifier.assigner.display`
* [STRING]    `related.target.display`
* [RECORD]    `specimen`
* [STRING]    `specimen.specimenId`
* [STRING]    `specimen.reference`
* [RECORD]    `specimen.identifier`
* [STRING]    `specimen.identifier.use`
* [RECORD]    `specimen.identifier.type`
* [RECORD]    `specimen.identifier.type.coding`
* [STRING]    `specimen.identifier.type.coding.system`
* [STRING]    `specimen.identifier.type.coding.version`
* [STRING]    `specimen.identifier.type.coding.code`
* [STRING]    `specimen.identifier.type.coding.display`
* [BOOLEAN]   `specimen.identifier.type.coding.userSelected`
* [STRING]    `specimen.identifier.type.text`
* [STRING]    `specimen.identifier.system`
* [STRING]    `specimen.identifier.value`
* [RECORD]    `specimen.identifier.period`
* [STRING]    `specimen.identifier.period.start`
* [STRING]    `specimen.identifier.period.end`
* [RECORD]    `specimen.identifier.assigner`
* [STRING]    `specimen.identifier.assigner.organizationId`
* [STRING]    `specimen.identifier.assigner.reference`
* [RECORD]    `specimen.identifier.assigner.identifier`
* [STRING]    `specimen.identifier.assigner.identifier.use`
* [RECORD]    `specimen.identifier.assigner.identifier.type`
* [RECORD]    `specimen.identifier.assigner.identifier.type.coding`
* [STRING]    `specimen.identifier.assigner.identifier.type.coding.system`
* [STRING]    `specimen.identifier.assigner.identifier.type.coding.version`
* [STRING]    `specimen.identifier.assigner.identifier.type.coding.code`
* [STRING]    `specimen.identifier.assigner.identifier.type.coding.display`
* [BOOLEAN]   `specimen.identifier.assigner.identifier.type.coding.userSelected`
* [STRING]    `specimen.identifier.assigner.identifier.type.text`
* [STRING]    `specimen.identifier.assigner.identifier.system`
* [STRING]    `specimen.identifier.assigner.identifier.value`
* [RECORD]    `specimen.identifier.assigner.identifier.period`
* [STRING]    `specimen.identifier.assigner.identifier.period.start`
* [STRING]    `specimen.identifier.assigner.identifier.period.end`
* [RECORD]    `specimen.identifier.assigner.identifier.assigner`
* [STRING]    `specimen.identifier.assigner.identifier.assigner.organizationId`
* [STRING]    `specimen.identifier.assigner.identifier.assigner.reference`
* [STRING]    `specimen.identifier.assigner.identifier.assigner.display`
* [STRING]    `specimen.identifier.assigner.display`
* [STRING]    `specimen.display`
* [RECORD]    `text`
* [STRING]    `text.status`
* [STRING]    `text.div`
* [RECORD]    `category`
* [STRING]    `category.text`
* [RECORD]    `category.coding`
* [BOOLEAN]   `category.coding.userSelected`
* [STRING]    `category.coding.version`
* [STRING]    `category.coding.code`
* [STRING]    `category.coding.display`
* [STRING]    `category.coding.system`
* [RECORD]    `code`
* [RECORD]    `code.coding`
* [BOOLEAN]   `code.coding.userSelected`
* [STRING]    `code.coding.version`
* [STRING]    `code.coding.code`
* [STRING]    `code.coding.display`
* [STRING]    `code.coding.system`
* [STRING]    `code.text`
* [RECORD]    `component`
* [RECORD]    `component.dataAbsentReason`
* [RECORD]    `component.dataAbsentReason.coding`
* [STRING]    `component.dataAbsentReason.coding.system`
* [STRING]    `component.dataAbsentReason.coding.version`
* [STRING]    `component.dataAbsentReason.coding.code`
* [STRING]    `component.dataAbsentReason.coding.display`
* [BOOLEAN]   `component.dataAbsentReason.coding.userSelected`
* [STRING]    `component.dataAbsentReason.text`
* [RECORD]    `component.interpretation`
* [RECORD]    `component.interpretation.coding`
* [STRING]    `component.interpretation.coding.system`
* [STRING]    `component.interpretation.coding.version`
* [STRING]    `component.interpretation.coding.code`
* [STRING]    `component.interpretation.coding.display`
* [BOOLEAN]   `component.interpretation.coding.userSelected`
* [STRING]    `component.interpretation.text`
* [RECORD]    `component.referenceRange`
* [RECORD]    `component.referenceRange.low`
* [FLOAT]     `component.referenceRange.low.value`
* [STRING]    `component.referenceRange.low.unit`
* [STRING]    `component.referenceRange.low.system`
* [STRING]    `component.referenceRange.low.code`
* [RECORD]    `component.referenceRange.high`
* [FLOAT]     `component.referenceRange.high.value`
* [STRING]    `component.referenceRange.high.unit`
* [STRING]    `component.referenceRange.high.system`
* [STRING]    `component.referenceRange.high.code`
* [RECORD]    `component.referenceRange.type`
* [RECORD]    `component.referenceRange.type.coding`
* [STRING]    `component.referenceRange.type.coding.system`
* [STRING]    `component.referenceRange.type.coding.version`
* [STRING]    `component.referenceRange.type.coding.code`
* [STRING]    `component.referenceRange.type.coding.display`
* [BOOLEAN]   `component.referenceRange.type.coding.userSelected`
* [STRING]    `component.referenceRange.type.text`
* [RECORD]    `component.referenceRange.appliesTo`
* [RECORD]    `component.referenceRange.appliesTo.coding`
* [STRING]    `component.referenceRange.appliesTo.coding.system`
* [STRING]    `component.referenceRange.appliesTo.coding.version`
* [STRING]    `component.referenceRange.appliesTo.coding.code`
* [STRING]    `component.referenceRange.appliesTo.coding.display`
* [BOOLEAN]   `component.referenceRange.appliesTo.coding.userSelected`
* [STRING]    `component.referenceRange.appliesTo.text`
* [RECORD]    `component.referenceRange.age`
* [RECORD]    `component.referenceRange.age.low`
* [FLOAT]     `component.referenceRange.age.low.value`
* [STRING]    `component.referenceRange.age.low.unit`
* [STRING]    `component.referenceRange.age.low.system`
* [STRING]    `component.referenceRange.age.low.code`
* [RECORD]    `component.referenceRange.age.high`
* [FLOAT]     `component.referenceRange.age.high.value`
* [STRING]    `component.referenceRange.age.high.unit`
* [STRING]    `component.referenceRange.age.high.system`
* [STRING]    `component.referenceRange.age.high.code`
* [STRING]    `component.referenceRange.text`
* [RECORD]    `component.code`
* [RECORD]    `component.code.coding`
* [BOOLEAN]   `component.code.coding.userSelected`
* [STRING]    `component.code.coding.version`
* [STRING]    `component.code.coding.code`
* [STRING]    `component.code.coding.display`
* [STRING]    `component.code.coding.system`
* [STRING]    `component.code.text`
* [RECORD]    `component.value`
* [RECORD]    `component.value.attachment`
* [STRING]    `component.value.attachment.contentType`
* [STRING]    `component.value.attachment.language`
* [STRING]    `component.value.attachment.data`
* [STRING]    `component.value.attachment.url`
* [INTEGER]   `component.value.attachment.size`
* [STRING]    `component.value.attachment.hash`
* [STRING]    `component.value.attachment.title`
* [STRING]    `component.value.attachment.creation`
* [RECORD]    `component.value.codeableConcept`
* [RECORD]    `component.value.codeableConcept.coding`
* [STRING]    `component.value.codeableConcept.coding.system`
* [STRING]    `component.value.codeableConcept.coding.version`
* [STRING]    `component.value.codeableConcept.coding.code`
* [STRING]    `component.value.codeableConcept.coding.display`
* [BOOLEAN]   `component.value.codeableConcept.coding.userSelected`
* [STRING]    `component.value.codeableConcept.text`
* [STRING]    `component.value.dateTime`
* [RECORD]    `component.value.period`
* [STRING]    `component.value.period.start`
* [STRING]    `component.value.period.end`
* [RECORD]    `component.value.range`
* [RECORD]    `component.value.range.low`
* [FLOAT]     `component.value.range.low.value`
* [STRING]    `component.value.range.low.unit`
* [STRING]    `component.value.range.low.system`
* [STRING]    `component.value.range.low.code`
* [RECORD]    `component.value.range.high`
* [FLOAT]     `component.value.range.high.value`
* [STRING]    `component.value.range.high.unit`
* [STRING]    `component.value.range.high.system`
* [STRING]    `component.value.range.high.code`
* [RECORD]    `component.value.ratio`
* [RECORD]    `component.value.ratio.numerator`
* [FLOAT]     `component.value.ratio.numerator.value`
* [STRING]    `component.value.ratio.numerator.comparator`
* [STRING]    `component.value.ratio.numerator.unit`
* [STRING]    `component.value.ratio.numerator.system`
* [STRING]    `component.value.ratio.numerator.code`
* [RECORD]    `component.value.ratio.denominator`
* [FLOAT]     `component.value.ratio.denominator.value`
* [STRING]    `component.value.ratio.denominator.comparator`
* [STRING]    `component.value.ratio.denominator.unit`
* [STRING]    `component.value.ratio.denominator.system`
* [STRING]    `component.value.ratio.denominator.code`
* [RECORD]    `component.value.sampledData`
* [RECORD]    `component.value.sampledData.origin`
* [FLOAT]     `component.value.sampledData.origin.value`
* [STRING]    `component.value.sampledData.origin.unit`
* [STRING]    `component.value.sampledData.origin.system`
* [STRING]    `component.value.sampledData.origin.code`
* [FLOAT]     `component.value.sampledData.period`
* [FLOAT]     `component.value.sampledData.factor`
* [FLOAT]     `component.value.sampledData.lowerLimit`
* [FLOAT]     `component.value.sampledData.upperLimit`
* [INTEGER]   `component.value.sampledData.dimensions`
* [STRING]    `component.value.sampledData.data`
* [STRING]    `component.value.string`
* [STRING]    `component.value.time`
* [RECORD]    `component.value.quantity`
* [STRING]    `component.value.quantity.comparator`
* [STRING]    `component.value.quantity.code`
* [STRING]    `component.value.quantity.system`
* [STRING]    `component.value.quantity.unit`
* [FLOAT]     `component.value.quantity.value`
* [RECORD]    `context`
* [STRING]    `context.display`
* [STRING]    `context.episodeOfCareId`
* [RECORD]    `context.identifier`
* [STRING]    `context.identifier.use`
* [RECORD]    `context.identifier.type`
* [RECORD]    `context.identifier.type.coding`
* [STRING]    `context.identifier.type.coding.system`
* [STRING]    `context.identifier.type.coding.version`
* [STRING]    `context.identifier.type.coding.code`
* [STRING]    `context.identifier.type.coding.display`
* [BOOLEAN]   `context.identifier.type.coding.userSelected`
* [STRING]    `context.identifier.type.text`
* [STRING]    `context.identifier.system`
* [STRING]    `context.identifier.value`
* [RECORD]    `context.identifier.period`
* [STRING]    `context.identifier.period.start`
* [STRING]    `context.identifier.period.end`
* [RECORD]    `context.identifier.assigner`
* [STRING]    `context.identifier.assigner.organizationId`
* [STRING]    `context.identifier.assigner.reference`
* [RECORD]    `context.identifier.assigner.identifier`
* [STRING]    `context.identifier.assigner.identifier.use`
* [RECORD]    `context.identifier.assigner.identifier.type`
* [RECORD]    `context.identifier.assigner.identifier.type.coding`
* [STRING]    `context.identifier.assigner.identifier.type.coding.system`
* [STRING]    `context.identifier.assigner.identifier.type.coding.version`
* [STRING]    `context.identifier.assigner.identifier.type.coding.code`
* [STRING]    `context.identifier.assigner.identifier.type.coding.display`
* [BOOLEAN]   `context.identifier.assigner.identifier.type.coding.userSelected`
* [STRING]    `context.identifier.assigner.identifier.type.text`
* [STRING]    `context.identifier.assigner.identifier.system`
* [STRING]    `context.identifier.assigner.identifier.value`
* [RECORD]    `context.identifier.assigner.identifier.period`
* [STRING]    `context.identifier.assigner.identifier.period.start`
* [STRING]    `context.identifier.assigner.identifier.period.end`
* [RECORD]    `context.identifier.assigner.identifier.assigner`
* [STRING]    `context.identifier.assigner.identifier.assigner.organizationId`
* [STRING]    `context.identifier.assigner.identifier.assigner.reference`
* [STRING]    `context.identifier.assigner.identifier.assigner.display`
* [STRING]    `context.identifier.assigner.display`
* [STRING]    `context.reference`
* [STRING]    `context.encounterId`
* [RECORD]    `effective`
* [RECORD]    `effective.period`
* [STRING]    `effective.period.start`
* [STRING]    `effective.period.end`
* [STRING]    `effective.dateTime`
* [STRING]    `id`
* [TIMESTAMP] `issued`
* [RECORD]    `meta`
* [TIMESTAMP] `meta.lastUpdated`
* [RECORD]    `meta.security`
* [STRING]    `meta.security.system`
* [STRING]    `meta.security.version`
* [STRING]    `meta.security.code`
* [STRING]    `meta.security.display`
* [BOOLEAN]   `meta.security.userSelected`
* [RECORD]    `meta.tag`
* [STRING]    `meta.tag.system`
* [STRING]    `meta.tag.version`
* [STRING]    `meta.tag.code`
* [STRING]    `meta.tag.display`
* [BOOLEAN]   `meta.tag.userSelected`
* [STRING]    `meta.versionId`
* [STRING]    `meta.profile`
* [STRING]    `status`
* [RECORD]    `subject`
* [STRING]    `subject.deviceId`
* [STRING]    `subject.display`
* [STRING]    `subject.groupId`
* [RECORD]    `subject.identifier`
* [STRING]    `subject.identifier.use`
* [RECORD]    `subject.identifier.type`
* [RECORD]    `subject.identifier.type.coding`
* [STRING]    `subject.identifier.type.coding.system`
* [STRING]    `subject.identifier.type.coding.version`
* [STRING]    `subject.identifier.type.coding.code`
* [STRING]    `subject.identifier.type.coding.display`
* [BOOLEAN]   `subject.identifier.type.coding.userSelected`
* [STRING]    `subject.identifier.type.text`
* [STRING]    `subject.identifier.system`
* [STRING]    `subject.identifier.value`
* [RECORD]    `subject.identifier.period`
* [STRING]    `subject.identifier.period.start`
* [STRING]    `subject.identifier.period.end`
* [RECORD]    `subject.identifier.assigner`
* [STRING]    `subject.identifier.assigner.organizationId`
* [STRING]    `subject.identifier.assigner.reference`
* [RECORD]    `subject.identifier.assigner.identifier`
* [STRING]    `subject.identifier.assigner.identifier.use`
* [RECORD]    `subject.identifier.assigner.identifier.type`
* [RECORD]    `subject.identifier.assigner.identifier.type.coding`
* [STRING]    `subject.identifier.assigner.identifier.type.coding.system`
* [STRING]    `subject.identifier.assigner.identifier.type.coding.version`
* [STRING]    `subject.identifier.assigner.identifier.type.coding.code`
* [STRING]    `subject.identifier.assigner.identifier.type.coding.display`
* [BOOLEAN]   `subject.identifier.assigner.identifier.type.coding.userSelected`
* [STRING]    `subject.identifier.assigner.identifier.type.text`
* [STRING]    `subject.identifier.assigner.identifier.system`
* [STRING]    `subject.identifier.assigner.identifier.value`
* [RECORD]    `subject.identifier.assigner.identifier.period`
* [STRING]    `subject.identifier.assigner.identifier.period.start`
* [STRING]    `subject.identifier.assigner.identifier.period.end`
* [RECORD]    `subject.identifier.assigner.identifier.assigner`
* [STRING]    `subject.identifier.assigner.identifier.assigner.organizationId`
* [STRING]    `subject.identifier.assigner.identifier.assigner.reference`
* [STRING]    `subject.identifier.assigner.identifier.assigner.display`
* [STRING]    `subject.identifier.assigner.display`
* [STRING]    `subject.locationId`
* [STRING]    `subject.reference`
* [STRING]    `subject.patientId`
* [RECORD]    `value`
* [RECORD]    `value.attachment`
* [STRING]    `value.attachment.contentType`
* [STRING]    `value.attachment.language`
* [STRING]    `value.attachment.data`
* [STRING]    `value.attachment.url`
* [INTEGER]   `value.attachment.size`
* [STRING]    `value.attachment.hash`
* [STRING]    `value.attachment.title`
* [STRING]    `value.attachment.creation`
* [BOOLEAN]   `value.boolean`
* [STRING]    `value.dateTime`
* [RECORD]    `value.period`
* [STRING]    `value.period.start`
* [STRING]    `value.period.end`
* [RECORD]    `value.range`
* [RECORD]    `value.range.low`
* [FLOAT]     `value.range.low.value`
* [STRING]    `value.range.low.unit`
* [STRING]    `value.range.low.system`
* [STRING]    `value.range.low.code`
* [RECORD]    `value.range.high`
* [FLOAT]     `value.range.high.value`
* [STRING]    `value.range.high.unit`
* [STRING]    `value.range.high.system`
* [STRING]    `value.range.high.code`
* [RECORD]    `value.ratio`
* [RECORD]    `value.ratio.numerator`
* [FLOAT]     `value.ratio.numerator.value`
* [STRING]    `value.ratio.numerator.comparator`
* [STRING]    `value.ratio.numerator.unit`
* [STRING]    `value.ratio.numerator.system`
* [STRING]    `value.ratio.numerator.code`
* [RECORD]    `value.ratio.denominator`
* [FLOAT]     `value.ratio.denominator.value`
* [STRING]    `value.ratio.denominator.comparator`
* [STRING]    `value.ratio.denominator.unit`
* [STRING]    `value.ratio.denominator.system`
* [STRING]    `value.ratio.denominator.code`
* [RECORD]    `value.sampledData`
* [RECORD]    `value.sampledData.origin`
* [FLOAT]     `value.sampledData.origin.value`
* [STRING]    `value.sampledData.origin.unit`
* [STRING]    `value.sampledData.origin.system`
* [STRING]    `value.sampledData.origin.code`
* [FLOAT]     `value.sampledData.period`
* [FLOAT]     `value.sampledData.factor`
* [FLOAT]     `value.sampledData.lowerLimit`
* [FLOAT]     `value.sampledData.upperLimit`
* [INTEGER]   `value.sampledData.dimensions`
* [STRING]    `value.sampledData.data`
* [STRING]    `value.time`
* [RECORD]    `value.codeableConcept`
* [RECORD]    `value.codeableConcept.coding`
* [BOOLEAN]   `value.codeableConcept.coding.userSelected`
* [STRING]    `value.codeableConcept.coding.version`
* [STRING]    `value.codeableConcept.coding.code`
* [STRING]    `value.codeableConcept.coding.display`
* [STRING]    `value.codeableConcept.coding.system`
* [STRING]    `value.codeableConcept.text`
* [RECORD]    `value.quantity`
* [STRING]    `value.quantity.comparator`
* [STRING]    `value.quantity.code`
* [STRING]    `value.quantity.system`
* [STRING]    `value.quantity.unit`
* [FLOAT]     `value.quantity.value`
* [STRING]    `value.string`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
