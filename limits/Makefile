# Build zip file for submission to MNRAS
#
# .pdf dependancies were generated with
#	pdflatexmk -deps ms | grep "\\.pdf"
#

#DEPS=\
#    ms.tex\
#    ms.bib\
#    ms.bbl\
#    myaasmacros.sty\
#    AAQuadR1a_Tms-a.pdf\
#    AAQuadR1a_Tms-b.pdf\
#    AAQuadR1a_Tms-c.pdf\
#    AAferror-1sig.pdf\
#    AAferror_profile-1sig.pdf\
#    AAferror_shape-1sig.pdf\
#    ACferror-1sig.pdf\
#    ACferror_profile-1sig.pdf\
#    ACferror_shape-1sig.pdf\
#    BBferror-1sig.pdf\
#    BBferror_profile-1sig.pdf\
#    BBferror_shape-1sig.pdf\
#    BCExtendedDoubleR1-nosymm_Tms-appendix-a-1.pdf\
#    BCExtendedDoubleR1-nosymm_Tms-appendix-b-1.pdf\
#    BCExtendedDoubleR1-nosymm_Tms-appendix-c-1.pdf\
#    BCExtendedDoubleR1-nosymm_Tms-appendix-d-1.pdf\
#    BCExtendedDoubleR1-nosymm_tms-appendix-a.pdf\
#    BCExtendedDoubleR1-nosymm_tms-appendix-b.pdf\
#    BCExtendedDoubleR1-nosymm_tms-appendix-c.pdf\
#    BCExtendedDoubleR1-nosymm_tms-appendix-d.pdf\
#    BCExtendedDoubleR1_tmS-a-1.pdf\
#    BCExtendedDoubleR1_tmS-b-1.pdf\
#    BCExtendedDoubleR1_tmS-c-1.pdf\
#    BCExtendedDoubleR1_tms-a.pdf\
#    BCExtendedDoubleR1_tms-b.pdf\
#    BCExtendedDoubleR1_tms-c.pdf\
#    BCQuadR1a-nosymm_Tms-appendix-a-1.pdf\
#    BCQuadR1a-nosymm_Tms-appendix-a.pdf\
#    BCQuadR1a-nosymm_Tms-appendix-b-1.pdf\
#    BCQuadR1a-nosymm_Tms-appendix-b.pdf\
#    BCQuadR1a-nosymm_Tms-appendix-c-1.pdf\
#    BCQuadR1a-nosymm_Tms-appendix-c.pdf\
#    BCQuadR1a-nosymm_Tms-appendix-d-1.pdf\
#    BCQuadR1a-nosymm_Tms-appendix-d.pdf\
#    BCQuadR1a-pr10_TmS-a.pdf\
#    BCQuadR1a-pr10_TmS-b.pdf\
#    BCQuadR1a-pr10_TmS-c.pdf\
#    BCQuadR1a-pr5_TmS-a.pdf\
#    BCQuadR1a-pr5_TmS-b.pdf\
#    BCQuadR1a-pr5_TmS-c.pdf\
#    BCQuadR1a-pr6_TmS-a.pdf\
#    BCQuadR1a-pr6_TmS-b.pdf\
#    BCQuadR1a-pr6_TmS-c.pdf\
#    BCQuadR1a-pr7_TmS-a.pdf\
#    BCQuadR1a-pr7_TmS-b.pdf\
#    BCQuadR1a-pr7_TmS-c.pdf\
#    BCQuadR1a_TmS-kappa-a.pdf\
#    BCQuadR1a_TmS-kappa-b.pdf\
#    BCQuadR1a_TmS_sigp-2.pdf\
#    BCQuadR1a_Tms-a.pdf\
#    BCQuadR1a_Tms-b.pdf\
#    BCQuadR1a_Tms-c.pdf\
#    BCQuadR1a_Tms_sigp-1.pdf\
#    BC_beta.pdf\
#    BCarrival_surfaces.pdf\
#    BCferror-1sig.pdf\
#    BCferror_profile-1sig.pdf\
#    BCferror_shape-1sig.pdf\
#    MockGalProfile-a.pdf\
#    MockGalProfile-b.pdf\
#    MockGalProfile-c.pdf

DEPS=\
    AAQuadR1a_Tms-a.pdf\
    AAQuadR1a_Tms-b.pdf\
    AAQuadR1a_Tms-c.pdf\
    AAferror-1sig.pdf\
    AAferror_profile-1sig.pdf\
    AAferror_shape-1sig.pdf\
    ACferror-1sig.pdf\
    ACferror_profile-1sig.pdf\
    ACferror_shape-1sig.pdf\
    BBferror-1sig.pdf\
    BBferror_profile-1sig.pdf\
    BBferror_shape-1sig.pdf\
    BCExtendedDoubleR1-nosymm_Tms-appendix-a-1.pdf\
    BCExtendedDoubleR1-nosymm_Tms-appendix-b-1.pdf\
    BCExtendedDoubleR1-nosymm_Tms-appendix-c-1.pdf\
    BCExtendedDoubleR1-nosymm_Tms-appendix-d-1.pdf\
    BCExtendedDoubleR1-nosymm_tms-appendix-a.pdf\
    BCExtendedDoubleR1-nosymm_tms-appendix-b.pdf\
    BCExtendedDoubleR1-nosymm_tms-appendix-c.pdf\
    BCExtendedDoubleR1-nosymm_tms-appendix-d.pdf\
    BCExtendedDoubleR1_tmS-a-1.pdf\
    BCExtendedDoubleR1_tmS-b-1.pdf\
    BCExtendedDoubleR1_tmS-c-1.pdf\
    BCExtendedDoubleR1_tms-a.pdf\
    BCExtendedDoubleR1_tms-b.pdf\
    BCExtendedDoubleR1_tms-c.pdf\
    BCQuadR1a-nosymm_Tms-appendix-a-1.pdf\
    BCQuadR1a-nosymm_Tms-appendix-b-1.pdf\
    BCQuadR1a-nosymm_Tms-appendix-c-1.pdf\
    BCQuadR1a-nosymm_Tms-appendix-d-1.pdf\
    BCQuadR1a-nosymm_tms-appendix-a.pdf\
    BCQuadR1a-nosymm_tms-appendix-b.pdf\
    BCQuadR1a-nosymm_tms-appendix-c.pdf\
    BCQuadR1a-nosymm_tms-appendix-d.pdf\
    BCQuadR1a-pr10_TmS-a.pdf\
    BCQuadR1a-pr10_TmS-b.pdf\
    BCQuadR1a-pr10_TmS-c.pdf\
    BCQuadR1a-pr5_TmS-a.pdf\
    BCQuadR1a-pr5_TmS-b.pdf\
    BCQuadR1a-pr5_TmS-c.pdf\
    BCQuadR1a-pr6_TmS-a.pdf\
    BCQuadR1a-pr6_TmS-b.pdf\
    BCQuadR1a-pr6_TmS-c.pdf\
    BCQuadR1a-pr7_TmS-a.pdf\
    BCQuadR1a-pr7_TmS-b.pdf\
    BCQuadR1a-pr7_TmS-c.pdf\
    BCQuadR1a_TmS-kappa-a.pdf\
    BCQuadR1a_TmS-kappa-b.pdf\
    BCQuadR1a_TmS_sigp-2.pdf\
    BCQuadR1a_Tms-a.pdf\
    BCQuadR1a_Tms-b.pdf\
    BCQuadR1a_Tms-c.pdf\
    BCQuadR1a_Tms_sigp-1.pdf\
    BC_beta.pdf\
    BCarrival_surfaces.pdf\
    BCferror-1sig.pdf\
    BCferror_profile-1sig.pdf\
    BCferror_shape-1sig.pdf\
    MockGalProfile-a.pdf\
    MockGalProfile-b.pdf\
    MockGalProfile-c.pdf\
    myaasmacros.sty\
    ms.bib\
    ms.bbl\
    ms.tex

mnras: $(DEPS)
	pdflatexmk ms
	pdf2ps ms.pdf
	zip ms.zip $(DEPS)

.PHONY: mnras
